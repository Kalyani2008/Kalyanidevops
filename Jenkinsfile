pipeline {
	agent any
	tools {
		maven 'maven 3.8.1'
		
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
