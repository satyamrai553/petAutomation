pipeline {
    agent any
    tools {
        maven 'maven' // Use the configured Maven name
    }
    stages {
        stage('Cleanup') {
    steps {
        sh 'rm -rf *'
    }
}
        stage('Test') {
            steps {
                sh 'mvn clean test'
            }
        }
    }
}
