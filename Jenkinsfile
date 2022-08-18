 pipeline{
     agent any
    stages{
        stage('Install Docker') {
            steps {
               sh 'curl https://get.docker.com/ > dockerinstall && chmod 777 dockerinstall && ./dockerinstall'
             }
        }
         stage('Build image') {
            steps {
               sh ' docker build . '
             }
        }
     }
   
 }

