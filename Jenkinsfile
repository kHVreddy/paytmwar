pipeline {
  agent any
  stages {
    stage('SCM') {
      steps {
        git(url: 'https://github.com/kHVreddy/paytmwar.git', branch: 'master', credentialsId: 'git_credentials')
      }
    }

  }
}