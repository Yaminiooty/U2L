pipeline {

   agent any
   
   environment {
        PATH = "$PATH:/usr/local/bin"
    }

   stages {
       stage('docker-compose') {
           steps {
              
              sh "docker-compose up -d"
              
           }
       }
   }
     
}
