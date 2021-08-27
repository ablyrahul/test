pipeline {
  agent any
  stages {
    stage('fetch branch') {
      steps {
        git(url: 'https://github.com/AblySoft268/AirSideChat', branch: 'master', credentialsId: '78d2419b-e0d6-4cdf-ad0a-fc3ae569cbd2')
      }
    }

  }
}