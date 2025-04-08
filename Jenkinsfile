pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git url: 'https://github.com/saylee028/git-jenk-test.git', branch: 'main'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the project...'
            }
        }

        stage('Test') {
            steps {
                echo 'Running all tests...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the project...'
            }
        }
    }
}
