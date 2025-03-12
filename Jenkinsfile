pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh '''
                ls -la
                javac Test.java
                java Test
                ls -la
                
                '''
            }
        }
    }
}
