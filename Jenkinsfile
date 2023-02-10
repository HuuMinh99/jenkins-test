pipeline {
    agent {
        docker {
            image 'python:3.10.6'
        }
    }
    stages {
        stage('Build') {
            steps {
                sh 'python --version'
                sh 'python test.py'
            }
        }
    }
}