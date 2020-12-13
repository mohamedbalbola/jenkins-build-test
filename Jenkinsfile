#!/usr/bin/groovy
pipeline {
    agent { docker { image 'python' } }

	stages {

		stage('Build') {
			steps {
				echo 'Building..'
			}
		}

		stage('Test') {
			steps {
				sh 'python --version'
			}
		}

		stage('Deploy') {
			steps {
				echo 'Deploying....'
			}
		}

	}
}
