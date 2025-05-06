pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Sabeshragav/jenkins-java.git'
            }
        }

        stage('Compile Java') {
            steps {
                bat 'javac hw.java'
            }
        }

        stage('Run Java') {
            steps {
                bat 'java hw'
            }
        }
    }
}
