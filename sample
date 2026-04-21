pipeline {
    agent any

    tools {
        jdk 'JDK17'
    }

    stages {
        stage('Compile') {
            steps {
                sh 'javac Demo2.java'
            }
        }

        stage('Run') {
            steps {
                sh 'java Demo2'
            }
        }
    }
}
