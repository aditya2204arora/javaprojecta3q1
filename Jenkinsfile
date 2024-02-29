pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                git 'https://github.com/aditya2204arora/javaprojecta3q1.git'
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
                echo 'Deploying...'
            }
        }
    }
}
