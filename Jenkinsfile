pipeline {
    agent any
    stages{
        stage('First Stage') {
            steps{
                sh 'docker run nginx'
                sh 'docker ps -q'
            }
        }
    }
}