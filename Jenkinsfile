pipeline {
     agent { label 'slave1' }
    stages {
        stage('Back-end') {
            agent {
                docker { image 'maven:3-alpine' }
            }
            
            steps {
                sh 'mvn --version'
            }
        }
        
    }
}
