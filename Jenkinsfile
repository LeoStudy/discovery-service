pipeline {
    agent any
    tools {
        maven 'M3'
    }
    stages {
        stage('Maven Clean') {
            steps {
                sh 'mvn clean'
            }
        }
        stage('Package') {
            steps {
                sh 'mvn package'
            }
        }
    }
}