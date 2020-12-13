#!/usr/bin/groovy
pipeline {
    agent { docker { image 'python:latest' } }

	stages {

		stage('Build') {
			steps {
				echo 'Building..'
			}
		}

		stage('Test') {
			steps {
				echo 'Testing'
			}
		}

		stage('Deploy') {
			steps {
				echo 'Deploying....'
			}
		}

	}
}
