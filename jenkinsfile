pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                bat 'javac Hello.java'
            }
        }
        
        stage('Run') {
            steps {
                bat 'java Hello'
            }
        } // Closes stage('Run')
    } // Closes stages
} // Closes pipeline
