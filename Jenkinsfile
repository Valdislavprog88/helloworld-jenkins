pipeline {
    agent {
        docker { image 'python:3.10' }
    }
    stages {
        stage('Task') {
            steps {
                sh 'python main.py'
            }
        }
    }
}