pipeline {
  agent {
      docker {
        image 'python:3'
        label 'my-build-agent'
      }
  }
  stages {
    stage('version') {
      steps {
        sh 'python3 --version'
      }
    }
    stage('hello') {
      steps {
        sh 'python3 hello.py'
      }
    }
  }
}
