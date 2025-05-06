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
                echo 'Compiling Java code...'
                bat 'javac hw.java'
            }
        }

        stage('Run Java') {
            steps {
                echo 'Running Java program...'
                bat 'java hw'
            }
        }
    }
}
