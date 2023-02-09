pipeline {

   agent any
   
     stages {
      stage('Checkout') {
            steps {
                
                git url: 'https://github.com/Yaminiooty/U2L.git', branch: 'main'
            }
                            }
       stage('docker-compose') {
           steps {
              sh "pwd"
              sh "docker-compose up -d"
              
           }
       }
   }
     
}
