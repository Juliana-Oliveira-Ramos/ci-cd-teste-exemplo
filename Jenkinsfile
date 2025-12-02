pipeline{
    agent any 

    stages{
        stage('Instalacao de dependencias'){
            steps{
                bat 'npm install'
                bat ''
            }
        }

         stage('Execucao dos testes'){
            steps{
                bat 'npm test'
            }
        }
    }








}