@Library('roboshop-shared-library@main') _
pipeline{
  agent any

  stages{

    //lint checks
    stage('Lint Checks'){
      steps{
        script{
          nodejs.lintChecks()
        }
      }
    }
  }
}