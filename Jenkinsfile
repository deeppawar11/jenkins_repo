pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/<deeppawar11>/<jenkins_repo>.git'
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
