pipeline {

   agent any
   
     stages {
       stage('checkout') {
           steps {
               
               sh " git clone https://github.com/Yaminiooty/U2L.git"
               sh "pwd"
               sh "ls -a"
               sh "mv U2L /home"
               sh "cd /home"
                             
                  }
           }
       stage('docker-compose') {
      
           steps {
              
              sh "docker-compose -f ~/home/U2L/docker-compose.yml up -d"
              
           }
       }
   }
}  

