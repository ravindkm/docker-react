node{
	stage('SCM Checkout'){
		git 'https://github.com/ravindkm/docker-react.git'
		sh 'cd /tmp'
		sh 'mkdir docker-react'
		sh 'cp * /tmp/docker-react'
	}
	stage('Compile-Package'){
		echo 'download done'
	}
}
