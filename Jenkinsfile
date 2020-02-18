pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Running build automation job'
        sh './gradlew build --no-daemon'
        archiveArtifacts 'dist/trainSchedule.zip'
      }
    }

    stage('Beez Beez') {
      steps {
        echo 'Buzz beez buzz'
      }
    }

  }
}