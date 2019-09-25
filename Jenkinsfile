pipeline {
	agent any
	stages {
	 stage('Buid Master') { 
	   when { 
	       branch 'master'		   
	   }
	   steps { 
	      echo 'Building Master'
	   }
	 }
	 stage (Build Dev') {
	   when {
		branch 'dev'
	   }
	   steps { 
		echo 'Building Dev'
	   }
	 }

	}
}
