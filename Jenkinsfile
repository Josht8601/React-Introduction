pipeline{
    agent any

    tools {node.js "node"}

    stages {

        stage('Install dependencies') {
            steps {
                sh 'npm install'
            }

        }

        stage('Test') {
            steps {
                sh 'npm test'
            }
        }

    }
}