pipeline {
	agent any
	stages {

		stage('Domain redirect blue') {
			steps {
				
				sh '''
					python3 --version
					whoami
				'''
				
			}
		}

		stage('aws') {
			steps {
				
				sh '''
					sudo /home/ubuntu/.local/bin/aws help

				'''
				
			}
		}
	}
}