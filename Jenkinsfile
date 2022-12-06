pipeline {
  triggers { cron('H 4/* 0 0 1-5') }
  agent {
  }
  stages {
    stage('trigger') {
      steps {
        sh 'curl https://my-worker.135972134215313.workers.dev/'
      }
    }
  }
}
