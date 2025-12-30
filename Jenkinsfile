pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Build Docker Image') {
            steps {
                sh 'docker build -t frontend:v2 frontend'
            }
        }

        stage('Tag Docker Image') {
            steps {
                sh 'docker tag frontend:v2 rishi1702/frontend:v2'
            }
        }

        stage('Push to DockerHub') {
            steps {
                sh 'docker push rishi1702/frontend:v2'
            }
        }
    }
}

