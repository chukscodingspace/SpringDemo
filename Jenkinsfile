 pipeline{
     agent any
    stages{
        stage('Install Docker') {
            steps {
               sh ' sudo apt install docker.io'
             }
        }
         stage('Build image') {
            steps {
               sh ' docker build . '
             }
        }
     }
   
 }

