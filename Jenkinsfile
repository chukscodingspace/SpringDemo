pipeline{
    agent { dockerfile true}
    stages{
        stage('Test'){
            Steps {
                sh '''
                docker --version
                git --version
                '''
            }
        }
    }
   
}