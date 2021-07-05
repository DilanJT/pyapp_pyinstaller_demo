pipeline {
    agent none
    stages {
        stage('build') {
            agent { 
                docker { 
                    image 'python:3.8.10' 
                } 
            }
            steps {
                sh 'python3 app.py'
            }
        }
    }
}