pipeline {
    agent {
        maître {
            image 'node:6-alpine' 
            args '-p 3000:3000' 
        }
    }
    maître {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}