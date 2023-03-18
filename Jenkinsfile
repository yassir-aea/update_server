pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                print "DEBUG: parameter IP_ADDRESS = ${IP_ADDRESS}"
                runuser -l master -c 'cd /home/test/ ; ansible-playbook -i inventory.yml nginx.yaml' 
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
