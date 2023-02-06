pipeline {
    agent any

    stages {
        
        stage('checkout codes ') {
            steps {
        git 'https://github.com/mustafagoek/react-redux-realworld-example-app-deploy-with-AzureDevops.git'

            }
        }
        stage('build docker') {
            steps {
                echo 'building docker'
                sh 'docker build -t test-pipeline .'
            }
        }
    }
}
