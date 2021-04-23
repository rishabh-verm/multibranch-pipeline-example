pipeline {

    agents any
    stages{

        stage('Master branch') {

            steps{
                sh 'javac hellomaster.java'
                sh 'java hellomaster'
            }
        }

    }
}