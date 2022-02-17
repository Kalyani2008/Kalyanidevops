pipeline {
	agent any
	tools {
		maven "3.6.1"
		
	}
	stages {
		stage('mavne-build'){
			steps {
				sh 'mvn clean install'
				}
			}
     stage('package'){
			steps {
				sh 'mvn package'
				}
			}
		}
}
