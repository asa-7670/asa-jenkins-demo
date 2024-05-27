pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                echo 'Checkout...'
            }
        }
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }
        stage('Quality') {
            steps {
                echo 'Quality...'
            }
        }
        stage('Deployment') {
            steps {
                echo 'Deploying ...'
            }
        }   
        stage('Docker build image') {
            steps {
                echo 'Docker build image ...'
            }
        }
        stage('Docker push image') {
            steps {
                echo 'Docker push image ...'
            }
        }
    }     
}
