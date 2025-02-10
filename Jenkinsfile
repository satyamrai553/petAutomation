pipeline {
    agent any
    tools {
        maven 'Maven-3.8.6' // Use the configured Maven name
    }
    stages {
        stage('Test') {
            steps {
                sh 'mvn clean test'
            }
        }
    }
}
