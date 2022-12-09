pipeline {
    agent any
    stages {
      stage("verify tools") {
          steps {
              sh '''
               echo sh(script: 'env|sort', returnStdout: true)              
               curl --version
                
              '''
          }
      }
 

    }
}