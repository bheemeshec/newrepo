pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                /var/lib/jenkins/apache-maven-3.6.1/mvn compile
            }
        }
        stage('Test') {
            steps {
                echo "mvn clean test"
            }
        }
        stage('package') {
            steps {
                echo "mvn clean package"
            }
        }
}
