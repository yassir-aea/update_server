pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                print "DEBUG: parameter IP_ADDRESS = ${IP_ADDRESS}"
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
