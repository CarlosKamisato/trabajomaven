pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'install'                
            }
        }

        stage('Test') {
            steps {
                sh 'test'               
            }
        }
        stage('Deploy') {
            steps {
                echo 'Desplegando el area de desarrollo'
            }
        }
    } 
}