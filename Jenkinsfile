node{
	stage('SCM Checkout'){
		sh 'cd /home/ec2-user'
		sh 'mkdir docker-react'
		git 'https://github.com/ravindkm/docker-react.git'
	}
	stage('Compile-Package'){
		echo 'download done'
	}
}
