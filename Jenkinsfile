pipeline {

   agent any
   
     stages {
              
       stage('docker-compose') {
           steps {
              sh "ls -a"
              sh "sudo docker-compose up -d"
              
           }
       }
   }
     
}
