@Library('my-shared-library@main') _  // Ensure the library name and branch are correct

pipeline {
    agent any
    stages {
        stage('Greet') {
            steps {
                script {
                    helloWorld('Jenkins User')  // Call function from shared library
                }
            }
        }
    }
}
