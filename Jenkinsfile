pipeline {

   agent any
   
     stages {
       stage('checkout') {
           steps {
               
               git url: ' https://github.com/Yaminiooty/U2L.git', branch: 'main' /root
               sh "cd root"
                  }
           }
       stage('docker-compose') {
      
           steps {
              sh "ls -a"
              sh "docker-compose up -d"
              
           }
       }
   }
     
}
