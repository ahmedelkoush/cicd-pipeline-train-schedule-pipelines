pipline {
  agent any
  stages {
    stage ('Compilation') {
		   steps {
	       echo 'Running Compilation automatically'
		   sh './gradlew build'
		   	}
			steps {
			echo 'Archiving artifacts'
			archiveArtifacts artifacts: 'dis/trainSchedule.zip'
	
			}
	    
  }
 }
}
