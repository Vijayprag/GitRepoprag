pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello Vijay & World"'
                sh '''
                    echo "Multiline shell steps works too vijay. This is a webhook triggred form github"
                    ls -lah
                '''
            }
        }
    }
}
