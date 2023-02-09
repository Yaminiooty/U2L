pipeline {

   agent any
   
     stages {
      
       stage('docker-compose') {
           steps {
              sh "cd /var/jenkins_home/workspace/U2L"
              sh"ls -a"
              sh "git clone https://github.com/Yaminiooty/U2L.git"
              sh "docker-compose up -d"
              
           }
       }
   }
     
}
