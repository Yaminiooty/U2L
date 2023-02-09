pipeline {

   agent any
   
     stages {
              
       stage('docker-compose') {
           steps {
              sh "ls -a"
              sh "docker-compose up -d"
              
           }
       }
   }
     
}
