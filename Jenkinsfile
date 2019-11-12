pipeline {
    agent any
    parameters {
        
        choice(name: 'CHOICE', choices: ['prod', 'uat', 'sit'], description: 'Pick something')
        
    }
    stages {
        stage('prod') {
            
            steps {
                checkout scm https://github.com/harish-oss/java.git
               stage('sit') {   
                   steps {
               echo "Choice: ${params.CHOICE}"
                   }
               }
            }
        }
    }
}
