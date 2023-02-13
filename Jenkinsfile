pipeline {

   agent any
   
     stages {
       stage('checkout') {
           steps {
               
               sh " git clone https://github.com/Yaminiooty/U2L.git"
               sh "pwd"
               sh "ls -a"
               sh "cd /var/jenkins_home/workspace/JenkinsPipeline"
               sh "ls -a"
               sh "mv U2L /home"
               sh "cd /home/U2L"

               
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

