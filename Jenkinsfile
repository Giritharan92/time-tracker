pipeline {
    agent any

    environment {
        secret = credentials('SECRET_PWD')
    }
    stages {
        stage('Build') {
            steps {
                sh 'echo $secret'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying'
            }
        }
    }
}
