pipeline {

   agent any
   
     stages {
       stage('docker-compose') {
           steps {
              sh "docker-compose --version"
              sh "/usr/bin/docker-compose up -d"
              
           }
       }
   }
     
}
