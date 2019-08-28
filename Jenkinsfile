pipeline {
  agent any
  stages {
    stage('Jenkins-Botium') {
      steps {
        sh '''curl http://192.168.99.100:4000/api/triggerbuild/AtosTeAyuda \\ 

  -H \': \' \\ 

  -H \'APIKEY: aQVe39FSWkIZ8pdU6ZZ5\' \\ 

  -H \'BUILDID: AtosTeAyuda-${BUILD_NUMBER}\' \\ 

  -H \'Content-Type: application/json\' \\ 

  -H \'TAG: Build${BUILD_NUMBER}\''''
      }
    }
  }
}