pipeline {
	agent any
	tools {
		maven "3.5.4"
		
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
