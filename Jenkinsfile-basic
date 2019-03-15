pipeline {
  agent { label 'linux' }
  stages {
    stage("test") {
      steps {
        sh """
          uname -a
          java -version
        """
      }
    }
  }
}
