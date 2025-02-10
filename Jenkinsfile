pipeline {
    agent any
    stages {
        stage('Build Project') {
            steps {
                bat 'dotnet build'
            }
        }
        stage('Run Tests') {
            steps {
                bat 'dotnet test'
            }
        }
    }
}