pipeline {
    agent any

    stages {

        stage('Check Node') {
            steps {
                bat 'node --version'
                bat 'npm --version'
            }
        }

        stage('Check Git') {
            steps {
                bat 'git --version'
            }
        }
    }
}