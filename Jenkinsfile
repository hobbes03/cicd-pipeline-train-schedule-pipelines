pipeline {
 agent any
  stages {
    satge('Build') {
      steps {
        echo 'Running build'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
        echo 'Build done'
      }
    }
  }
}
