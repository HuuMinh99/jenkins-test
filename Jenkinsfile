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
                    to: '1862882611',
                    messenge: 'sdsdsds'
                )
            }
        }
    }
}
