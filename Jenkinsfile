pipeline {

   agent any
   
     stages {
      stage('Checkout') {
            steps {
                
                git url: 'https://github.com/Yaminiooty/U2L.git', branch: 'main'
            }
                            }
       stage('docker-compose') {
           steps {
              sh "cd /var/jenkins_home/workspace/U2L"
              sh"ls -a"
              sh "docker-compose up -d"
              
           }
       }
   }
     
}
