pipeline {
    agent any
    options {
        buildDiscarder(logRotator(artifactDaysTokeepStr: '', artifactNumToKeepStr: '5', daysToKeepStr: '' , numToKeepStr: '5'))
        disableConcurrentBuilds()
    }
    stages {
        stage ('Echo String') {
            steps {
                echo 'Hello, this is a simple Jenkinsfile'
            }
        }
    }
}
