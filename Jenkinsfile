pipeline {
  agent any
  stages {
    stage('Install Python') {
      steps {
        sh 'apt-get update'
        sh 'apt-get install python3 -y'
            }
    }
    stage('test2') {
      steps {
        sh 'python test.py'
      }   
    }
  }
}
