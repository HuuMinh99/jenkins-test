pipeline {
  agent { 
      image 'maven:3-alpine' 
      args '-v /root/.m2:/root/.m2' 
   }
  stages {
    stage('pwd1') {
      steps {
        sh 'pwd'
        echo '1234'
            }
    }
    stage('git clone') {
      steps {
        sh 'cd /var'
        sh 'git clone https://github.com/HuuMinh99/Microservices.git'
        echo '123456'
        sh 'pwd'
      }   
     }
     stage('Build') {
            steps {
                sh 'mvn clean install'
            }
        }
  }
}
