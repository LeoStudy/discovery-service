pipeline {
    agent any
    tools {
        maven 'M3'
    }
    stages {
        stage('Maven Clean') {
            steps {
                sh 'mvnw clean'
            }
        }
        stage('Package') {
            steps {
                sh 'mvnw package'
            }
        }
    }
}