pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Fetching code'
            }
        }

        stage('List Files') {
            steps {
                sh 'pwd'
                sh 'ls -lrt'
            }
        }

        stage('Read README') {
            steps {
                sh 'cat README.md'
            }
        }
    }
}
