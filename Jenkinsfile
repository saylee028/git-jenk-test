pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/saylee028/git-jenk-test.git'

            }
        }

        stage('Build') {
            steps {
                echo 'Building the project...'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the project...'
            }
        }
    }
}
