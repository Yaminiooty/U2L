pipeline {

   agent any
   
     stages {
       stage('checkout') {
           steps {
               sh " cd /home "
               sh " mkdir U22L"
         
               sh " git clone https://github.com/Yaminiooty/U2L.git /home/U22L"
               sh "pwd"
              
                             
                  }
           }
       stage('docker-compose') {
      
           steps {
              
              sh "docker-compose -f /home/U22L/docker-compose.yml up -d"
              
           }
       }
   }
}  

