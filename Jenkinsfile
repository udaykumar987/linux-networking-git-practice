pipeline {
    agent any

    stages {

        stage('Build Docker Image') {
            steps {
                sh 'docker build -t linux-practice:v2 .'
            }
        }

        stage('Remove Old Container') {
            steps {
                sh 'docker rm -f linux-container || true'
            }
        }

        stage('Run Container') {
            steps {
                sh '''
                docker run -d \
                --name linux-container \
                -p 8081:80 \
                linux-practice:v2
                '''
            }
        }
    }
}
