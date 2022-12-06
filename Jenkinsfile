pipeline {
  agent any
  stages {
    stage('trigger') {
      steps {
        sh 'curl https://my-worker.135972134215313.workers.dev/'
      }
    }

  }
  triggers {
    cron('* * * * *')
  }
}