pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        echo 'Running The Buid'
        sh './ gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
         }
      }
   }
}
