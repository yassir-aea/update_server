pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'ls -alt'
                sh 'mkdir test'
                sh 'rm -rf test'
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying.....'
            }
        }
    }
}
