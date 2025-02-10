pipeline {
    agent any
    tools {
        maven 'maven' // Use the configured Maven name
    }
    stages {
        stage('Test') {
            steps {
                sh 'mvn clean test'
            }
        }
    }
}
