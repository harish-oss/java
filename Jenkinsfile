pipeline {
    agent any
    parameters {
       

        choice(name: 'CHOICE', choices: ['One', 'Two', 'Three'], description: 'Pick something')

        
    stages {
        stage('Example') {
            steps {
               
                echo "Choice: ${params.CHOICE}"

               
            }
        }
    }
}
