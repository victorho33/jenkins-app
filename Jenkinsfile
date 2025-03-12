pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh '''
                ls -la
                javac Tester.java
                ls -la

                '''
            }
        }
        stage('Test') {
            steps {
                sh '''
                ls -la
                java Tester
                ls -la
                '''
            }
        }
    }
}
