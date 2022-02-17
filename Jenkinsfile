pipeline {
	agent any
	tools {
		maven 'maven 3.8.1'
		
	}
	stages {
		stage('mavne-build'){
			steps {
				sh 'mvn clean package -DskipTests'
				}
			}
     stage('package'){
			steps {
				sh 'mvn package'
				}
			}
		}
}
