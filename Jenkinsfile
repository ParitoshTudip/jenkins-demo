pipeline {
  agent any

  environment {
    BRANCH_NAME = "${env.BRANCH_NAME}"
  }

  triggers {
        cron('H/2 * * * *')
  }

  stages {

    stage('Checkout code'){
      steps {
        echo "Application running for branch: ${BRANCH_NAME}"
      }
    }

    stage('Build'){
      steps {
        echo "Building the application...."
      }
    }

    stage('Test'){
      steps {
        echo "Running Tests...."
      }
    }

    stage('Deploy'){
      steps {
        echo "Deploying Application...."
      }
    }
  }
}