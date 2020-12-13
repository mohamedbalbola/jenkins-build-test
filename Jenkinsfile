#!/usr/bin/groovy
pipeline {
    agent any 

	stages {

		stage('Build') {
			steps {
				python name.py
			}
		}

		stage('Test') {
			steps {
				python name.py
			}
		}

		stage('Deploy') {
			steps {
				echo 'Deploying....'
			}
		}

	}
}
