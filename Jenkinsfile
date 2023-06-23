pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                sh 'python hello.py' 
                // stash(name: 'compiled-results', includes: 'sources/*.py*') 
            }
        }
    }
}