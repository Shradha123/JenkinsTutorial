pipeline {
    agent any

    tools {nodejs "node"}

    stages {
        stage('Build') {
            steps {
               sh 'npm config ls'
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