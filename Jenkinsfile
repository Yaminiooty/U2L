pipeline {
    agent { docker { image 'docker' } }

    stages {
        stage('build') {
            steps {
                sh 'docker build -t my-container U2L/u2l_backend/'
            }
        }
    }
}
