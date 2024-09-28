pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git branch: 'Aziz-Khalsi---Devops', url: 'https://github.com/azizkhalsi/Devops.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building...'
                // Add your build commands here (e.g., maven, gradle, npm)
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                // Add your test commands here (e.g., unit tests)
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Add your deploy commands here
            }
        }
    }
}
