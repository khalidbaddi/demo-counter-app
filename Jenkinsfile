pipeline {

    agent any 

    stages{

        stage ('Git checkout'){

            steps{
                git branch: 'main', url: 'https://github.com/khalidbaddi/demo-counter-app.git'
            }
        }
        stage ('UNIT TESTING'){

            steps{
                sh 'mvn test'
            }
        }
    }
}
