node {
    stage('GIT') 
         { 
            git 'https://github.com/gkdevops/PetClinic'
         }
              
    stage('Build')
         {
            tool name: 'Maven', type: 'maven'
            sh 'mvn package'
             
          }
              
}
