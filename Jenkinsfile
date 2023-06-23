pipeline {
    agent {
        label 'python'
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