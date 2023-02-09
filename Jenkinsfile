pipeline {

   agent any
   
     stages {
       stage('checkout') {
           steps {
               
               git url: ' https://github.com/Yaminiooty/U2L.git', branch: 'main'
               sh "mkdir Jenrepo"
                // Change file permisson
                sh "pwd"
              
                sh "mv -R * Jenrepo/"
                sh "cd Jenrepo"
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
