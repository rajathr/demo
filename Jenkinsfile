pipeline {
    agent { dockerfile true }
    stages {
        stage('Build') {
            steps {
                sh 'sudo su'
                sh 'mvn clean install dockerfile:build'
            }
        }
    }
}
