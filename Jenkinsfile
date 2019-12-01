pipeline {
agent any
    stages {
        stage('checkout') {
            steps {
                git 'https://github.com/yehiamc/Jenkins-test.git'
            }
        }
        stage('build') {
            steps {
                bat 'python 1.py'
            }
        }
    }
}
