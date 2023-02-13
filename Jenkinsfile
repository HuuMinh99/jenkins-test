pipeline {
  agent { 
      image 'maven:3-alpine' 
      args '-v /root/.m2:/root/.m2' 
   }
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
