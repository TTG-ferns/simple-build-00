pipeline {
    agent { dockerfile true }
    stages {
        stage('Test') {
           node {
             label "master"
           }
            steps {
                sh 'node --version'
                sh 'svn --version'
            }
        }
    }
}