#!/usr/bin/env groovy
// Jenkinsfile (Declarative Pipeline)

pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Compile') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Testing') {
            steps {
                echo 'Testing....'
            }
        }
		stage('Sonar') {
           steps {
                echo 'Sonar....'
            }
		}
		stage('Deploy') {
           steps {
                echo 'Deploying....'
        }
	  }
	}
}
