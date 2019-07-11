pipeline {
	agent any
	stages {
		stage('Read YAML file') {
			steps {
				script {
					data = readYaml (file: 'application.yml') 
				}
				echo data.toString()
			}
		}
	}
}