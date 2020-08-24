pipeline {
   agent any
   stages {
     stage ('Build') {
       echo 'Running The Build'
       sh ./'gradlew build --no-daemon'
       archiveArtifacts artifacts: 'dist/trainSchedule.zip'
     }
   }
}
