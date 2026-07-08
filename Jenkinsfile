pipeline {

    agent any

    tools {
        jdk 'Java21'
        maven 'Maven3'
    }

    stages {

        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }

    }
}
