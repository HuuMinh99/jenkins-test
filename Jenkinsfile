// pipeline {
//     agent {
//         node {
//             label 'Slave1'
//         }
//     }
//     stages {
//         stage('Clone Repository') {
//             steps {
//                 git branch: 'master', url: 'https://github.com/HuuMinh99/Microservices.git'
//             }
//         }
//         stage('send messenger to telegram'){
//             steps{
//                 telegramSend(
//                     to: '1862882611',
//                     messenge: 'Build Status is $BUILD_URL :: $BUILD_STATUS'
//                 )
//             }
//         }
//     }
// }
pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello'
            }
        }
        stage('Send notification') {
            steps {
                telegramSend(
                    to: '5952008889',
                    message: 'Build has finished'
                )
            }
        }
    }
}
