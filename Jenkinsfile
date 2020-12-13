#!/usr/bin/groovy
pipeline {
    agent any 

	stages {

		stage('Build') {
			steps {
				sh 'python name.py'
			}
		}

		stage('Test') {
			steps {
				sh 'python name.py'
			}
		}

		stage('Deploy') {
			steps {
				echo 'Deploying....'
			}
		}

	}
}
