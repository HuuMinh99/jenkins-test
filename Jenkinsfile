pipeline {
    agent {
        docker {
            image 'python:3.10.6'
            args '-v /var/run/docker.sock:/var/run/docker.sock'
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