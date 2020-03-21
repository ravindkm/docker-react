node{
	stage('SCM Checkout'){
		git 'https://github.com/ravindkm/docker-react.git'
		sh 'mkdir /tmp/docker-react1'
		sh 'cp -R * /tmp/docker-react1'
	}
	stage('Compile-Package'){
		echo 'download done'
	}
	stage('Docker build'){
		docker build -f Dockerfile.dev -t my-jenkins-docker:latest .
	}
}
