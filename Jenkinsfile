pipeline {
    agent any

    stages {
        stage('Install Java') {
            steps {
                sh '''
                    sudo apt-get update -y
                    sudo apt-get install -y openjdk-11-jdk
                '''
            }
        }

        stage('Build') {
            steps {
                echo 'Building project...'
                sh 'echo "Simulating build step..."'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                sh 'java -version'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application...'
            }
        }
    }
}
