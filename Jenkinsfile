pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                sh 'echo "Building step completed"'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                sh 'echo "Testing step completed"'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                sh 'echo "Deployment step completed"'
            }
        }
    }
}
