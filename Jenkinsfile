#!groovy

node {
	current.build = "SUCCESS"

	tools {
		maven 'Maven'
		jdk 'Java'
	}
	stages {
		stage ('Intialize') {
		steps {
			echo "PATH = %PATH%"
			echo "MAVEN = %MAVEN_HOME%"
		}
		}
		stage ('build') {
			steps {
				bat 'mvn clean install'
			}
		}
	}
}
			

