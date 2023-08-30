pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }
        
        stage('Build') {
            steps {
                echo 'Building the application...'
                // In a real application, you might run build commands here.
            }
        }
        
        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
                // In a real application, you might run deployment commands here.
            }
        }
    }
}
