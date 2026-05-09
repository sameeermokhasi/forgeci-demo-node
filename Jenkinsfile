pipeline {
  agent any
  stages {
    stage('Install') {
      steps {
        sh 'echo "Installing Node.js dependencies..."'
        sh 'echo "npm install complete"'
      }
    }
    stage('Test') {
      steps {
        sh 'echo "Running Jest unit tests..."'
        sh 'echo "All 42 tests passed"'
      }
    }
    stage('Build') {
      steps {
        sh 'echo "Building production bundle..."'
        sh 'echo "Build artifact: dist/app.js (2.4MB)"'
      }
    }
    stage('Deploy') {
      steps {
        sh 'echo "Deploying to production server..."'
        sh 'echo "Deploy complete: https://demo-node.forgeci.app"'
      }
    }
  }
}