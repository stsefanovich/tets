pipeline {
    agent { label 'common_slave' }

    stages {
        stage('Build') {
            steps {
                echo 'Building.'
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
