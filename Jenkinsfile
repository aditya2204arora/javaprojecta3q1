pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                git url: 'https://github.com/aditya2204arora/javaprojecta3q1.git', branch: 'main'
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
