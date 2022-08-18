 pipeline{
  agent {
   dockerfile true
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

