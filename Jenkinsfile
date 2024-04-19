pipeline {
    agent any 

    stages {
        stage('ocmpile') {
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