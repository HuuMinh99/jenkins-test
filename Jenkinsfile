pipeline {
  agent { docker { image 'python:3.10.6' } }
  stages {
    stage('Install Python') {
      steps {
        sh 'apt-get update -y'
        sh 'apt-get install python3 -y'
            }
    }
    stage('test2') {
      steps {
        sh 'python3 test.py'
      }   
     }
  }
}
