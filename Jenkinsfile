pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Construyendo la aplicacion'
                //sh 'mvn clear install'                
            }
        }

        stage('Test') {
            steps {
                echo 'Ejecutar los tests '
                //sh 'mvn test'               
            }
        }
        stage('Deploy') {
            steps {
                echo 'Desplegando el area de desarrollo'
                //sh 'java -jar /var/jenkins_home/workspace/trabajomaven/target/trabajomaven-1.0-SNAPSHOT.jar'
            }
        }
    } 
}