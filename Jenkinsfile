pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh '''
                ls -la
                javac Tester.java
                java Tester
                ls -la

                '''
            }
        }
    }
}
