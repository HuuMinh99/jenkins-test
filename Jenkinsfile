pipeline {
    agent {
        node {
            label 'Slave1'
        }
    }
    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'master', url: 'https://github.com/HuuMinh99/Microservices.git'
            }
        }
    }
}
