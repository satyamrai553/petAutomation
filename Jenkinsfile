pipeline {
    agent any
    tools {
        maven 'maven' // Use the configured Maven name
    }
    stages {
        stage('Test') {
            steps {
                bat 'mvn clean test'
            }
        }
    }
}
