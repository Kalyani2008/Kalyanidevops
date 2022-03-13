pipeline {
	agent any
	tools {
		maven 'maven 3.8.1'
		
	}
	stages {
		stage('Clean and Install') {
            steps {
                sh 'install - DskipTests'
            }
        }
        stage ('Package'){
            steps {
                sh 'mvn package'
             }
        }	
	}	
}
