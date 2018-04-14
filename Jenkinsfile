pipeline {
    agent { docker { image 'maven:3.3.3' } }
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