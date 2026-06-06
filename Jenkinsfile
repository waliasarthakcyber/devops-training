pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Hello from GitHub Jenkinsfile'
            }
        }

        stage('Info') {
            steps {
                sh 'pwd'
                sh 'whoami'
            }
        }
    }
}
