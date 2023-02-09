pipeline {

   agent any
   
     stages {
      
       stage('docker-compose') {
           steps {
              sh "cd /var/jenkins_home/workspace/U2L"
              sh"ls -a"
              sh "docker-compose up -d"
              
           }
       }
   }
     
}
