pipeline {
    agent { 
      dockerfile true
      label 'master-docker'
      }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
                sh 'svn --version'
            }
        }
    }
}