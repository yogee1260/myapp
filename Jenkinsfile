pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git url: 'https://github.com/yogee1260/myapp.git', branch: 'main'
            }
        }

        stage('Build') {
            steps {
                echo "Build Step"
            }
        }

        stage('Test') {
            steps {
                echo "Test Step"
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploy Step"
            }
        }
    }
}
