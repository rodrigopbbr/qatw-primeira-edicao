pipeline {
    agent any

    stages {
        stage('Node.Js Deps') {
            steps {
                sh 'npm install'
            }
        }
        stage('E2E Tests') {
            steps {
                sh 'npx plawright test'
            }
        }
    }
}
