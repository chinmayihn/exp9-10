pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'javac Main.java'
            }
        }

        stage('Test') {
            steps {
                bat 'java Main.java'
            }
        }
    }
}
