pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/Mahigautam27/jenkins-ci-demo.git'
            }
        }

        stage('Build') {
            steps {
                echo 'No build needed'
            }
        }

        stage('Test') {
            steps {
                bat '"C:\\Python313\\python.exe" -m pip install pytest'
                bat '"C:\\Python313\\python.exe" -m pytest'
            }
        }
    }
}