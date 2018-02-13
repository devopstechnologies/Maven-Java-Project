#!groovy

pipeline {
	agent {
		label "windows"
	}
	tools {
		maven "Maven3.5.2"
		jdk "java8"
	}
	stages {
		stage {'Intialize'} {
		steps {
			echo "PATH = $PATH"
			echo "MAVEN = $MAVEN_HOME"
		}
		}
		stage {'build'} {
			steps {
				bat 'mvn clean install'
			}
		}
	}
}
			
