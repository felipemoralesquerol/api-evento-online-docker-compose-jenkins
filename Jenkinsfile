pipeline {
    agent any
    stages {
      stage("verify tools") {
          steps {
              sh '''
               docker version
               docker-compose version 
              '''
          }
      }
      stage("docker-compose up") {
          steps {
              sh '''
              docker-compose up
              '''
          }
      }
 
    }
}