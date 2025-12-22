pipeline {
  agent any

  environment {
    BRANCH_NAME = "${env.BRANCH_NAME}"
  }
  stages {

    stage('Checkout code'){
      steps {
        echo "Runnig pipeline for branch:: ${BRANCH_NAME}"
      }
    }

    stage('Build'){
      steps {
        echo "Building the application for ${BRANCH_NAME} branch"
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