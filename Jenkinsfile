@Library('my-shared-library') _
pipeline {
  agent any 
  tools {
    maven 'mymaven'
  }
  stages {
    stage("code") {
      steps {
        checkoutcode()
      }
    }
    stage("build") {
      steps {
        mavenbuild()
      }
    }
  }
}
