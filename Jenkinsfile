pipeline{
    agent none
    stages{
        stage("Clone Repository"){
            agent { label 'master' }
            steps{
                git 'https://github.com/mgviscarra/spring-boot-blog.git'
                sh "echo Cloned!"
            }
          }
     }
 }
         
