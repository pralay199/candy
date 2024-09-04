pipeline {
    agent any

    environment {
        DOCKER_IMAGE = 'your-image-name:latest'
    }

    stages {

        
        stage('Build Docker Image') {
            steps {
                script {
                    // Build Docker image
                    sh 'cd new && docker compose up --build '
                }
            }
        }
        
  }


}
