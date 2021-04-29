pipeline {
    agent any
    tools {
        maven 'maven363'
    }
    stages {
        stage('Build') {
            stage('get maven verion') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
