 pipeline {
	agent any
     stages {
	  stage('Build on k8') {
		steps {
			sh 'pwd'
			sh 'ls -ltr'
			sh 'pwd'
			sh '/usr/local/bin/helm upgrade --install mzmhelloworld --set image.repository=registry.hub.docker.com/mzm1/devopjava --set image.tag=latest'
			}
		}

	}

}	
