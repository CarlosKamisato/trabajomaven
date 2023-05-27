pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Construyendo la aplicacion'
                sh 'mvn -B -DskipTests clean package'
            }
        }

        stage('Test') {
            steps {
                echo 'Ejecutar los tests '
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