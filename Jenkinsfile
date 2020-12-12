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
<<<<<<< HEAD
				python name.py
=======
				echo 'Test has been over..'
>>>>>>> bc4163332acf4ef3e954e299311c3647108c59f2
			}
		}

		stage('Deploy') {
			steps {
				echo 'Deploying....'
			}
		}

	}
}
