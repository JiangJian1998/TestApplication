pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Test"
                    ls -lah
                '''
            }
        }
    }
}