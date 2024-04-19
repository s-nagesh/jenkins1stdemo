pipeline {
    agent any 

    stages {
        stage('compile') {
            steps {
                sh 'node index.js'
            }
        }

        stage('run') {
            steps {
                sh 'node index'
            }
        }
    }
}