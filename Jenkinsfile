@Library('my-shared-library') _  // Load library (configured in Jenkins)

pipeline {
    agent any
    stages {
        stage('Greet') {
            steps {
                helloWorld('Jenkins User')  // Call the function from shared library
            }
        }
    }
}
