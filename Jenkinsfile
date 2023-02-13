pipeline {
  agent { docker { image 'python:3.10.6' } }
  stages {
    stage('pwd1') {
      steps {
        sh 'pwd'
            }
    }
    stage('git clone') {
      steps {
        sh 'cd /var'
        sh 'git clone https://github.com/HuuMinh99/Microservices.git'
        sh 'pwd'
      }   
     }
  }
}
