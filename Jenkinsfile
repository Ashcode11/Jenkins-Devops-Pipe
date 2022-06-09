pipeline {
	agent any
	stages {
		stage('Build') {
			steps {
			echo "Build"
         	
			}
		}
				stage('Test') {
			steps {
					echo "Test"
			       	
			}
		}
				stage('Integration Test') {
			steps {
				echo "Integration Test"
         	
			}
		}
	} 
	post {
		always {
			echo "i am awesome i run always"
		} 
		success {
			echo "i only run when you are successful"
		}
		failure {
			echo "i run on failure"
		}
	}
}