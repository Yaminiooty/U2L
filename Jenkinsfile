pipeline {

   agent any
   
     stages {
        stage('clone') {
           steps {
              
              git clone https://github.com/Yaminiooty/U2L.git XYZ
              sh "cd XYZ"
           
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
