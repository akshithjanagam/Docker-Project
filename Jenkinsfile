
pipeline {
  agent any 
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
