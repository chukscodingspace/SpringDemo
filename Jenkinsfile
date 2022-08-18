 pipeline{
     agent any
    stages{
        stage('Install Docker') {
            steps {
              sh 'apt update'
               sh 'apt install docker.io'
             }
        }
         stage('Build image') {
            steps {
               sh ' docker build . '
             }
        }
     }
   
 }

