pipeline {

   agent any
   
     stages {
       stage('checkout') {
           steps {
               
               sh " git clone https://github.com/Yaminiooty/U2L.git"
               sh "pwd"
               sh "ls -a"
               sh "mv U2L /root"
               sh "ls -a"
                             
                  }
           }
       stage('docker-compose') {
      
           steps {
              sh "cd /root"
              sh "docker-compose -f /U2L/docker-compose.yml up -d"
              
           }
       }
   }
}  

