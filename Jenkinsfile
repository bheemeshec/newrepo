pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                mvn compile
            }
        }
        stage('Test') {
            steps {
                mvn clean test
            }
        }
        stage('package') {
            steps {
                mvn clean package
            }
        }
    }
}
