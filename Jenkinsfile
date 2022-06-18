@Library('roboshop-shared-library@main') _
pipeline{
  agent any

  stages{

    //lint checks
    stage('Lint Checks'){
      steps{
        nodejs.lintChecks()
      }
    }
  }
}