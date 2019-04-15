pipeline {
  agent {
    dockerfile {
      filename 'dfsd'
    }

  }
  stages {
    stage('stageq') {
      steps {
        fingerprint 'sdfsf'
        sh 'echo hello'
        archiveArtifacts(allowEmptyArchive: true, artifacts: 'dfsdf', excludes: 'aas', fingerprint: true, onlyIfSuccessful: true)
        timeout(time: 5, activity: true) {
          dir(path: 'rtrt')
        }

      }
    }
  }
  environment {
    a = 'a'
  }
}