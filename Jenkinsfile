node {
	stage 'Checkout'
   	git url: 'https://github.com/ansayyad/Ansible_EC2_Tomcat_Deploy_Project1'
	stage 'Build'
	sh './myBuild.sh'
	stage 'Deploy'
	sh './myDeployment.sh'
  }
