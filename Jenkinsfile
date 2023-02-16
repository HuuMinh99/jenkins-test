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
        stage('send messenger to telegram'){
            steps{
                telegramSend(
                    to: '35702912',
                    messenge: 'Build Status is $BUILD_URL :: $BUILD_STATUS'
                )
            }
        }
    }
}
