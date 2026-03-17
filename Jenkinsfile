pipeline {
    agent any

    stages {

        stage('Clone Code') {
            steps {
                git branch: 'main', url: 'https://github.com/firdose0402/node-docker-devops-project.git'
            }
        }

        stage('Build Docker Image') {
            steps {
                sh 'docker build -t node-devops-app .'
            }
        }

        stage('Run Container') {
            steps {
                sh 'docker run -d -p 3000:3000 node-devops-app || true'
            }
        }

    }
}
