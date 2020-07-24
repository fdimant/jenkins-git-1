pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Ola Mundo"'
            }
        }
        stage('List') {
            steps {
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
