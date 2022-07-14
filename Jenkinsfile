pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'mvn package'
            }
        }
        stage('Test') {
            steps {
               sh 'mvn test'
            }
        }
        stage('Deploy') {
            steps {
                sh 'java -jar target/*.jar 10 20'
            }
        }
    }
}
