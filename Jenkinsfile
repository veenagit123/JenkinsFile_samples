pipeline {
    
    agent any
        stages{
            stage('GIT') 
               {
                steps{
                      git 'https://github.com/gkdevops/PetClinic'
                     }
               }
            stage('Build')
               {
                steps{
                      withMaven(maven :Maven){
                        sh "mvn clean package" 
                        }
                     }
                }       
              }
}
