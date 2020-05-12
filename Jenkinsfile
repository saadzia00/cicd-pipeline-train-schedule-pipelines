pipeline{
  agent any
  stages{
    stage('Build'){
      steps{
        echo 'This is Build'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  }

}
