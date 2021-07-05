pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('build') {
            agent {
                docker {
                    image 'python:3.8' 
                }
            }
            steps {
                sh 'python --version'
            }
        }
    }
}