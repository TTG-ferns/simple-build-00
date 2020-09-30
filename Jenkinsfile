pipeline {
    agent { 
      docker {
            image 'maven:3-alpine'
            args '-v $HOME/.m2:/root/.m2'        
            label 'master'
      }
    }
    stages {
        stage('Test') {
            steps {
                sh 'mvn -B'
            }
        }
    }
}