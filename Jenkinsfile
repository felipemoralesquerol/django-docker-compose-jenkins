pipeline {
    agent any
    stages {
      stage("verify tools") {
          steps {
              sh '''
               docker version
               docker info
               curl --version
                
              '''
          }
      }
 

    }
}