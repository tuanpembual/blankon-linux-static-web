pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                echo 'Hello world!' 
            }
            steps {
                sh 'npm install'
                sh 'npm run build'
            }
        }
    }
}

