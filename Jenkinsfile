pipeline {
    agent any
    stages {
        stage('Hello') {
            steps {
                echo 'Hello Python!'
                sh 'python3 --version || python --version'
            }
        }
        stage('Run Python') {
            steps {
                sh 'python3 main.py || python main.py'
            }
        }
    }
}
