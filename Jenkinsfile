pipeline {

   agent any
   
     stages {
       stage('checkout') {
           steps {
               sh " cd /home "
               sh " mkdir U22L"
         
               sh " git clone https://github.com/Yaminiooty/U2L.git /home/U22L"
               sh "pwd"
               sh " cd /home/U22L"
               sh "pwd"
              
                             
                  }
           }
       stage('docker-compose') {
      
           steps {
              
              sh "docker-compose up -d"
              
           }
       }
   }
}  

