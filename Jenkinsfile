pipeline {
    agent any
    stages {
      stage("verify tools") {
          steps {
              sh '''
               env             
               curl --version
               docker version
               docker info 
              '''
          }
      }
 

    }
}