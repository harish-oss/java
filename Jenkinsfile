pipeline {
    agent any
    parameters {
     
        choice(name: 'CHOICE', choices: ['prod', 'sit', 'uat'], description: 'Pick something')
       
    }
    stages {
        stage('Example') {
            steps {
                when { branch 'master' }
                           
                echo "Choice: ${params.CHOICE}"
                                
            }
        }
    }
}
