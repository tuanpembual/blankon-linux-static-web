pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                echo 'Hello world!' 
            }
            steps {
                npm install
                npm run build
            }
        }
    }
}

