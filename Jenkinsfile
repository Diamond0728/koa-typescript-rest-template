pipeline {
    agent { docker 'node: 10.16.3' }
    stages {
        stage('build') {
            steps {
                bat 'npm --version'
            }
        }
    }
}