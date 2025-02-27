@Library('my-shared-library') _  // Ensure the library name is correct

pipeline {
    agent any
    stages {
        stage('Greet') {
            steps {
                script {
                    helloWorld('Jenkins User')  // Call the function from shared library
                }
            }
        }
    }
}
