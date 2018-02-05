pipeline {
  agent any
  stages {
	
	try{
		stage('Clone') {
		  checkout scm
		}
		stage('Compile') {
		  steps {
			sh 'echo "Checkout Stage."'
		}
		}
		stage('Build') {
		  steps {
			sh 'echo "Checkout Stage."'
		  }  
		}
		stage('Artifact') {
		  steps {
			sh 'echo "Checkout Stage."'
		}
		}
		stage('Release Notes') {
		  steps {
			sh 'echo "Checkout Stage."'
		}
	  }
	 } catch (err) {
        currentBuild.result = 'FAILED'
        throw err
    }
  }
  environment {
    Owner = 'Srikanth'
  }
}