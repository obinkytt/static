pipeline {
    agent any

    stages {
        stage('Upload to AWS') {
            steps {
                sh 'echo "Hello World"'
               sh '''
                 echo "Multiline Shell steps works too"
                 ls -lah
                 '''
            }
        }
    }
}

