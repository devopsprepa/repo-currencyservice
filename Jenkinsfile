pipeline {
  agent any
  stages {
    stage('SCA') {
      steps {
        sh 'sonar-scanner   -Dsonar.projectKey=currencyservice   -Dsonar.sources=.   -Dsonar.host.url=http://43.205.241.89:9000   -Dsonar.token=sqp_a346d9e95edb3258d9d99d06c9374a1bd211d083'
      }
    }

  }
}