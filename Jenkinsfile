pipeline {
  agent { docker { image 'python:3.10.6' } }
  stages {
    stage('pwd1') {
      steps {
        sh 'pwd'
            }
    }
    stage('git clone repo2') {
      steps {
        sh 'cd /home'
        sh 'git clone https://github.com/HuuMinh99/Microservices.git'
        sh 'pwd'
      }   
     }
  }
}
