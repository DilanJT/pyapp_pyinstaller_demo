pipeline {
    agent none
    stages {
        stage('build') {
            agent any
            steps {
                sh 'python3 app.py'
            }
        }
    }
}