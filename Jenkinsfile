pipeline {
    agent any

    tools {
        nodejs 'NodeJS 16'
    }

    stages {
        stage('Install dependencies') {
            steps {
                sh 'npm install'
            }
        }

        stage('Run tests') {
            steps {
                sh 'npm test'
            }
        }

        stage('Build') {
            steps {
                echo 'Build step (opsional, disesuaikan dengan project)'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploy step (opsional, jika memungkinkan)'
            }
        }
    }
}
