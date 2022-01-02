pipeline
{
  agent any
    
  Stages
  {
  stage (Build)
    {
      echo 'Running build automation'
      sh './gradlew build --no-daemon'
      archiveArtifacts artifacts: 'dist/trainSchedule.zip'
    }
  }
    
  
  
}
