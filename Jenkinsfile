 pipeline{
     agent any
    stages{
        stage('Install Docker') {
            steps {
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

