pipeline{

    agent any

    stages{

        stage('Run Tests'){
            steps{
                sh "docker-compose up"

            }
        }

        stage('Bring grid down'){
            steps{
                sh "docker-compose down"
            }

            }
        }

    }

