pipeline{
  agent any

  stages{

    //lint checks
    stage('Lint Checks'){
      steps{
        sh '''
          #~/node_modules/jslint/bin/jslint.js server.js
          echo lint checks
        '''
      }
    }
  }
}