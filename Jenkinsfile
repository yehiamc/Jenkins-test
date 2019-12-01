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
                sh 'python 1.py'
            }
        }
    }
}
