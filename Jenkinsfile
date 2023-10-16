pipeline {
	agent any
	tools {
		jdk 'jdk11'
	}	
	stages {
		stage('hello') {
			steps {
				sh 'echo Hello Jenkins!'
			}
		}
		stage('test casc env') {
			steps {
				echo "JCasC env.hello ${env.hello}"
			}
		}
		stage('env') {
			steps {
				sh 'java --version'
			}
		}
	}
}
