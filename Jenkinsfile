// Updated Jenkinsfile
pipeline {
    agent any

    stages {
        stage('Verify') {
            steps {
                bat 'dir'
            }
        }

        stage('Build Docker Image') {
            steps {
                bat 'docker build -t dockerjvc79/github-demo .'
            }
        }

        stage('Push Docker Image') {
            steps {
