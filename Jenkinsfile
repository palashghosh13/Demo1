
pipeline {
  agent any
  stage {
	stage('Build') {
		steps {
			sh 'echo "Hello World"'
		}
	}
	stage('Buildmore') {
			steps {
				sh '''
					echo "Multipleline shell works too"
					ls -lah
				'''
			}
	  }
	}
  }
