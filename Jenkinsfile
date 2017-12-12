node {

	//Git Checkout
	stage ('Checkout') {
		checkout scm
	}

	//Build and SonarQube Analysis
	stage ('Build') {
		sh "${BRANCH_NAME}"
	}
	

	stage ('Docker Compose') {
		sh "sleep 60s"
  }
	
	//Deploying/Downloading Artifacts to Artifactory and Build Promotions
	stage ('Deploy Artifacts') {
	
		}
	
	stage ('Email Notifications') {
		//notifySuccessful()
	}
}
