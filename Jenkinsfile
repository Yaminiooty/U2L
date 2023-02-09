pipeline {

   agent any
   
     stages {
        stage('clone') {
           steps {
              sh "mkdir URLrepo"
              sh "cd URLrepo"
              git init
              git clone https://github.com/Yaminiooty/U2L.git
              
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
