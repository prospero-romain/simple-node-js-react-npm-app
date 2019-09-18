pipeline {
    agent {
        any {
            image 'node:6-alpine' 
            args '-p 3000:3000' 
        }
    }
    any {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}
