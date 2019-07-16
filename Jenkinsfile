pipeline {
  agent any
  stages {
    stage('Build1') {
      steps {
        archiveArtifacts(allowEmptyArchive: true, artifacts: 'Hello-World')
      }
    }
  }
}