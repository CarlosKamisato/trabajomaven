pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Construyendo la aplicacion'
                sh 'mvn clean compile'                
            }
        }

        stage('Test') {
            steps {
                echo 'Ejecutar los tests '
                sh 'mvn test'               
            }
        }
        stage('Deploy') {
            steps {
                echo 'Desplegando el area de desarrollo'
                sh 'mvn install'
            }
        }
    } 
}