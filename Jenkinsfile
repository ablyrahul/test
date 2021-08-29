pipeline {
  agent any
  stages {
    stage('fetch branch') {
      steps {
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[url: 'https://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@github.com/AblySoft268/YoCoach.git']]])
      }
    }

  }
}
