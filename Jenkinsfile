pipeline {

   agent any
   
     stages {
       stage('checkout') {
           steps {
               
               sh " git clone https://github.com/Yaminiooty/U2L.git /home"
               sh "pwd"
              
                             
                  }
           }
       stage('docker-compose') {
      
           steps {
              
              sh "docker-compose -f /home/U2L/docker-compose.yml up -d"
              
           }
       }
   }
}  

