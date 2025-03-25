pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/girixxz/simple-landing-page.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building project...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying application...'
            }
        }
    }
}
