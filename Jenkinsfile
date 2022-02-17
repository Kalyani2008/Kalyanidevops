pipeline {
	agent any
	tools {
		maven 'apache-maven'
		
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
