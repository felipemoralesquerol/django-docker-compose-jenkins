pipeline {
    agent any
    stages {
      stage("verify tools") {
          steps {
              sh '''
               echo $USER              
               curl --version
                
              '''
          }
      }
 

    }
}