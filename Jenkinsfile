pipeline {
    agent any
    stages {
      stage("verify tools") {
          steps {
              sh '''
               docker version
               
               curl --version
                
              '''
          }
      }
 

    }
}