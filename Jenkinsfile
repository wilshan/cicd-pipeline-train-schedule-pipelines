pipeline {
  agent any
  stages {
    stage ('build') {
      steps {
        echo 'Running CD by Wilshan'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
        }
       }
      }
     }
