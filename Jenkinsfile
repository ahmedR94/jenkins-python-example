pipeline {
    agent any
    tools {
      // Define the Python environment
      python 'python3'
    }
    stages {
        stage('Build') { 
            steps {
                sh 'python hello.py' 
                // stash(name: 'compiled-results', includes: 'sources/*.py*') 
            }
        }
    }
}