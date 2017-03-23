pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'This is a minimal build'
        input(message: 'Trigger Me!', id: 'trigger-me', ok: 'Thanks')
      }
    }
  }
}