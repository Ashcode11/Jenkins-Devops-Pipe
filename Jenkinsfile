//SCRIPTED
//node {
//	stage('Build') {
//		echo "Build"
//	}
//	stage('Test') {
//		echo "Test"
//	}
//	stage('Integration Test') {
//		echo "Test"
//	}
//}

//node {
//		echo "Build"
//		echo "Test"
//		echo "Integration Test"
//	
//}

//DECLARATIVE PIPELINE

pipeline {
	agent any
	stages {
		stage('Build') {
			steps {
			echo "Build 2"
         	}
		}
			stage('Test') {
			steps {
			 	echo "Test 2"
		    			}
		}
			stage('Integration Test') {
			steps {
		    echo "Integration Test 2"
			}
		}
	}
}
