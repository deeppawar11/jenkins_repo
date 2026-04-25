pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/<your-username>/<repo-name>.git'
            }
        }
        stage('Compile') {
            steps {
                sh 'javac HelloWorld.java'
            }
        }
        stage('Execute') {
            steps {
                sh 'java HelloWorld'
            }
        }
    }
}
