pipeline {
  agent any
  stages {
     stage ("scripts") {
        steps{
            sh '''
		 
		 ip a
		 jenkins --version
       		 pwd
		 who
		 uptime
		 java -version
	       '''
         }
     }
  }
}
