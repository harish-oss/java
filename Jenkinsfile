pipeline {
    agent {label 'dev'
         docker{ image 'maven:3-alpine' }
          }
    stages {
        stage('Back-end') {
            steps {
                sh 'mvn --version'
            }
        }
        
    }
}
