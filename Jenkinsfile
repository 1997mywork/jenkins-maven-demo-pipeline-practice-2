pipeline {
    agent any

    stages {

        stage('Clone') {
            steps {
                echo 'Cloning Repository'
            }
        }

        stage('Build') {
            steps {
                echo 'Building Application'
                sh 'mvn clean package'
            }
        }

        stage('Test') {
            steps {
                echo 'Running Tests'
                sh 'mvn test'
            }
        }

    }
}
