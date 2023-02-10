pipeline {
  agent any
  stages {
    stage('Install Python') {
      steps {
        sh 'sudo apt-get update'
        sh 'sudo apt-get install python3 -y'
            }
    }
    stage('test2') {
      steps {
        sh 'python test.py'
      }   
    }
  }
}