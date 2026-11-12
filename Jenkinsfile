
@Library('my-shared-library') _

pipeline {
    agent any

    tools {
        maven 'mymaven'
    }

    stages {
        stage('Code Checkout') {
            steps {
                checkoutcode()
            }
        }

        stage('Build') {
            steps {
                mavenbuild()
            }
        }
    }
}
