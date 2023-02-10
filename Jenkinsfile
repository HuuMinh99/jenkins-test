pipeline {
  agent { docker { image 'python:3.10.6' } }
  stages {
    stage('test1') {
      steps {
        echo 'hello'
      }
    }
    stage('test2') {
      steps {
        sh 'python test.py'
      }   
    }
  }
}