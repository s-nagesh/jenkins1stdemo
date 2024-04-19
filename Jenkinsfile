pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'node index.js'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}