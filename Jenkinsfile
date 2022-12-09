pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'setup.sh'
            }
        }
        stage('Test') {
            steps {
                sh 'curl localhost'
            }
        }
        stage('Deploy') {
            steps {
                echo 'I will add it to my TODO'
                //
            }
        }
    }
}