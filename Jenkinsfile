
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
