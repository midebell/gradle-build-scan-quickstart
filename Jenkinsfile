pipeline {
  agent {
    label 'windows2'
  }
  stages {
    stage('Build') {
      steps {
        bat """
          ./gradlew build --scan
        """
      }
    }
  }
}
