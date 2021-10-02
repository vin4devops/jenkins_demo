pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Checksout source code'
            }
        }
        stage('Build') {
            steps {
                echo 'Builds the code'
            }
        }
        stage('Tests') {
            steps {
                echo 'Does some sanity testing'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Does the deployment'
            }
        }
    }
    
}
