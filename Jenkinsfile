pipeline {
    agent any

    

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
