#!/usr/bin/groovy
pipeline {
	agent { docker { image 'python:3.5.1' } }

	stages {

		stage('Build') {
			steps {
				echo 'Building..'
			}
		}

		stage('Test') {
			steps {
				python "name.py"
			}
		}

		stage('Deploy') {
			steps {
				echo 'Deploying....'
			}
		}

	}
}
