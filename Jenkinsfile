pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

            steps {
                
                    bat 'mvn clean compile'
                bat 'sleep2'
                
            }
        }

        stage ('Testing Stage') {

            steps {
                
                    bat 'mvn test'
                bat 'sleep2'
               
            }
        }


        stage ('Deployment Stage') {
            steps {
              
                    bat 'mvn deploy'
               bat 'sleep2'
            }
        }
    }
}
