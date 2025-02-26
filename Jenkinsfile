pipeline {
    agent any
    
    stages {
        stage('Checkout Code') {
            steps {
                // Lấy code từ repo
                git branch: 'main', url: 'https://github.com/lamtranhahuy/jenkins-demo.git'
            }
        }
        
        stage('Build') {
            steps {
                echo "Building the application..."
                sh 'echo "Simulating build..."'
            }
        }
        
        stage('Test') {
            steps {
                echo "Running tests..."
                sh 'echo "Simulating tests..."'
            }
        }
        
        stage('Deploy') {
            steps {
                echo "Deploying application..."
                sh 'echo "Simulating deployment..."'
            }
        }
    }
}
