pipeline {

   agent any
   
     stages {
       stage('checkout') {
           steps {
               sh '''
                cd /home 
                mkdir U22L
                git clone https://github.com/Yaminiooty/U2L.git /home/U22L
                chmod 777 *
                 pwd
                cd /home/U22L
                pwd
                docker-compose up -d
                          '''   
                  }
           }
       
   }
}  

