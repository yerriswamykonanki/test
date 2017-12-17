node {

	//Git Checkout
	stage ('Checkout') {
		checkout scm
	}

	//Build and SonarQube Analysis
	stage ('Build') {
		sh "echo ${BRANCH_NAME}"
	}
	

	stage ('Docker Compose') {
		sh 'env >Jenkins_env'
	}
	
	//Deploying/Downloading Artifacts to Artifactory and Build Promotions
	stage ('Deploy Artifacts') {
	
		}
	
	stage ('Email Notifications') {
		//notifySuccessful()
	}
}
