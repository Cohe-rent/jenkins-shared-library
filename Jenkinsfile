@Library('jenkins-shared-library') _  // Match the Jenkins global library name

pipeline {
    agent any
    stages {
        stage('Greet') {
            steps {
                script {
                    helloWorld('Jenkins User')  // Calls vars/helloWorld.groovy
                }
            }
        }
    }
}
