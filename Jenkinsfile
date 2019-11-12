pipeline {
    agent any
    parameters {
        
        choice(name: 'CHOICE', choices: ['prod', 'uat', 'sit'], description: 'Pick something')
        
    }
    stages {
        stage('Example') {
            steps {
               echo "Choice: ${params.CHOICE}"
            }
        }
    }
}
