pipeline {

    agent any

    tools {
        jdk 'Java21'
        maven 'Maven3'
    }
    stage('Environment Check') {
    steps {
        sh 'java -version'
        sh 'mvn -version'
        sh 'echo $JAVA_HOME'
        sh 'which java'
        sh 'which mvn'
    }
}

