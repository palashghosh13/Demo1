  pipeline {
  agent any
  stage {
	stage('Build') {
		steps {
			sh 'echo "Hello World"'
			sh '''
				echo "Multipleline shell works too. This a Webhook tiggered from github"
				ls -lah
				'''
		}
	}
  }
}
