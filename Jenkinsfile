#!groovy

node {
	currentbuild.RESULT = "SUCCESS"

	stage ('compiling'){
		bat 'mvn clean install'
	}
}
