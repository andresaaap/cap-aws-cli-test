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
					echo para | sudo -S /home/ubuntu/.local/bin/aws

				'''
				
			}
		}
	}
}