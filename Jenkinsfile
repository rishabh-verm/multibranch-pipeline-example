pipeline {
    agent any
    stages {
        stage('main branch') {
            steps{
                sh 'javac hello.java'
                sh 'java hello'
            }
        }
    }
}
