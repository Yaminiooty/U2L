pipeline {
    agent { docker { image 'docker' } }

    stages {
        stage('build') {
            steps {
                sh 'docker build -t my-container .'
            }
        }
    }
}
