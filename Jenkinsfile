pipeline {

   agent any
   
     stages {
       stage('checkout') {
           steps {
               
               git url: ' https://github.com/Yaminiooty/U2L.git', branch: 'main'
               sh "mkdir Mydir"
                // Change file permisson
                sh "pwd"
              
                sh "mv /var/jenkins_home/workspace/JenkinsPipeline /Mydir"
                sh "cd Mydir"
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
