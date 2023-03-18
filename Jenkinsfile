pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                ls -alt
                echo 'test 1'
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
