pipeline {

    agent any

    stages {

        stage('Checkout') {
            steps {
                echo "Downloading Source Code..."
            }
        }

        stage('Build') {
            steps {
                sh 'node app.js'
            }
        }

    }
}
