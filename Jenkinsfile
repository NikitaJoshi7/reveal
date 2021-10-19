pipeline {
    agent any 
    stages {
        stage('Clone the repo') {
            steps {
                echo 'clone the repo'
                
                cleanWs()
                sh 'rm -rf Reveal'
                sh 'git clone https://github.com/NikitaJoshi7/reveal.git' 
                sh 'pwd'
                sh 'cd /var/lib/jenkins/workspace/q8'
                sh 'chmod 777 index.html'
                
            }
        }
       
    }
}
