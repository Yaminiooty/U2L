pipeline {

   agent any
   
     stages {
       stage('checkout') {
           steps {
               
               sh " git clone https://github.com/Yaminiooty/U2L.git"
               sh "pwd"
               sh "ls -a"
                             
                  }
           }
       stage('docker-compose') {
      
           steps {
              
              sh "docker-compose -f ~/var/jenkins_home/workspace/JenkinsPipeline/docker-compose.yml up -d"
              
           }
       }
   }
}  

