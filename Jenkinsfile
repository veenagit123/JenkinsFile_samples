node {
    stage('GIT') 
         { 
            git 'https://github.com/gkdevops/PetClinic'
         }
              
    stage('Build')
         {
            def myhome=tool name: 'Maven', type: 'maven'
             sh "${myhome}/bin/mvn package"
             
          }
              
}
