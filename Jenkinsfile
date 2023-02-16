
checkout scm

pipeline {
	agent any
	options {
		timestamps()
		timeout(time: 10, unit: 'HOURS')
	}
	environment {
		PATH = "${env.HOME}/.local/bin:${env.PATH}"
	}
	stages {
		stage('Test'){
			steps{
				sh "echo test-123"
			}
		}