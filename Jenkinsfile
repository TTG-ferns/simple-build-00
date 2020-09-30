pipeline {
    agent { 
      dockerfile true
      label 'master'
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