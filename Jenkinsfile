pipeline {

    agent any

    tools {
        jdk 'Java21'
        maven 'Maven3'
    }

    stages {

        stage('Checkout') {
            steps {
                git 'https://github.com/Potscorp/java-devops-demo.git'
            }
        }

        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }

    }

}
