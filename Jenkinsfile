pipeline {
	agent any
	stages {
		stage ('build') {
			steps {
				echo "Build"
			}
		}
		stage ('test: integration-&-quality') {
			steps {
			echo "Integration & quality"
			}
		}
		stage ('test: functional') {
			steps {
			echo "Functional test"
			}
		}

		stage ('deploy:prod') {
			steps {
			echo "Production deploy"
			}
		}
	}
}