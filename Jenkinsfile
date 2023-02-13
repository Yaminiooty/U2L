pipeline {

   agent any
   
     stages {
       stage('checkout') {
           steps {
               
               sh " git clone https://github.com/Yaminiooty/U2L.git"
               sh "pwd"
              
                             
                  }
           }
       stage('docker-compose') {
      
           steps {
              
              sh "docker-compose -f /U2L/docker-compose.yml up -d"
              
           }
       }
   }
}  

