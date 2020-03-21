node{
	stage('SCM Checkout'){
		git 'https://github.com/ravindkm/docker-react.git'
		sh 'mkdir -p /tmp/docker-react-proj'
		sh 'cp -R * /tmp/docker-react-proj'
	}
	stage('Compile-Package'){
		echo 'download done'
	}
	stage('Docker build'){
		sh 'cd /tmp/docker-react-proj'
		sh 'docker build -f Dockerfile.dev -t ravindkm/my-jenkins-docker:latest .'
		
	}
}
