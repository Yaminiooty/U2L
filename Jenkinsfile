pipeline {

   agent any

   stages {
       stage('docker-compose') {
           steps {
              
              sh "/usr/bin/docker-compose up -d"
              
           }
       }
   }
     
}
