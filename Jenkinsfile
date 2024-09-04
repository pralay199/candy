pipeline {
    agent {
        label 'my_new_node'
    }

    environment {
        DOCKER_IMAGE = 'your-image-name:latest'
    }

    stages {

        
        stage('Build Docker Image') {
            steps {
                script {
                    // Build Docker image
                    sh 'sudo docker compose up --build '
                }
            }
        }
        
  }


}
