 pipeline{
  agent {
   docker{ image 'node:16-alpine'}
  }
    stages{
        stage('Install Docker') {
            steps {
               sh 'node -version'
             }
        }
         stage('Build image') {
            steps {
               sh 'echo hello world '
             }
        }
     }
   
 }

