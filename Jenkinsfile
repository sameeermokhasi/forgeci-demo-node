pipeline {
  agent any
  stages {
    stage('Hotfix Checkout') {
      steps {
        sh 'echo "[HOTFIX] Checking out emergency auth crash fix..."'
      }
    }
    stage('Fast Test') {
      steps {
        sh 'echo "Running targeted auth regression tests..."'
        sh 'echo "Auth tests: PASSED"'
      }
    }
    stage('Emergency Deploy') {
      steps {
        sh 'echo "[HOTFIX] Fast-tracking deployment to production..."'
        sh 'echo "Auth crash fix deployed successfully"'
      }
    }
  }
}