pipeline {
  agent  any
  options {
  buildDiscarder(logRotator(numToKeepStr: '5'))
  }
  triggers {
    cron('*/1 * * * *')
  }  
  stages {
    stage ("stage 1") {
      steps {
        echo "Tanmay Agrawal"
      }

  }
  }
}
