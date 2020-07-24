pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Ola Mundo 2"'
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
