pipeline{
    agent none
    stages{
        stage("Clone Repository"){
            agent{label 'master'}
            steps{
                git https://github.com/DenisHerrera/DevOps.git
                sh "echo Cloned"
            }
         }
     }   
}
