pipeline {
    agent any

    stages {
        stage('Clone') {
            steps { git 'https://github.com/your-username/ci-cd-automation.git' }
        }
        stage('Build') { steps { echo 'Building...' } }
        stage('Test') { steps { sh 'python3 -m unittest test_app.py' } }
        stage('Deploy') { steps { echo 'Deploying...' } }
    }
}
