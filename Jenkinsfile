pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh'mvn package'
            }
        }
        stage('Test') {
            steps {
                'mvn test'
            }
        }
        stage('Deploy') {
            steps {
                echo 'wget'
            }
        }
    }
}
