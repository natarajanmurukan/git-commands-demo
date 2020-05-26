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
		stage ('test: load-&-security') {
			steps {
			echo "Security Testing"
			}
		}
		stage ('approval') {
			steps {
			echo "Approaval"
			}
		}
		stage ('deploy:prod') {
			steps {
			echo "Production deploy"
			}
		}
	}
}