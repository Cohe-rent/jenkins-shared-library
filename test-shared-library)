@Library('my-shared-library') _  // Load the Shared Library

pipeline {
    agent any
    stages {
        stage('Test Shared Library') {
            steps {
                script {
                    helloWorld()  // Call the shared library function
                }
            }
        }
    }
}
