pipeline {
    agent any

    stages {

        stage('Build Docker Image') {
            steps {
                bat 'docker build -t josh801251/my-html-app:latest .'
            }
        }

        stage('Push to Docker Hub') {
            steps {
                bat 'docker push josh801251/my-html-app:latest'
            }
        }

    }
}
