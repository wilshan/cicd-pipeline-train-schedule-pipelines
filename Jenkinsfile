pipeline {
  agent any
  stages {
    stage ('build') {
      steps {
        echo 'Running CD by Wilshan'
        sh './gradlew build'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
        }
       }
      }
     }
