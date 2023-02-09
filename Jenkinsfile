pipeline {

   agent any
   
     stages {
       stage('checkout') {
           steps {
              
               git url: ' https://github.com/Yaminiooty/U2L.git', branch: 'main'
                // Change file permisson
                sh "pwd"
                sh "chmod +x -R ./U2L" 
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
