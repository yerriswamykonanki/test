
node {

	//Git Checkout
	stage ('Checkout') {
		checkout scm
	}

	//Build and SonarQube Analysis
	stage ('Build') {
		sh '''git rev-parse --abbrev-ref HEAD > GIT_BRANCH'
    git_branch = readFile('GIT_BRANCH').trim()
    echo git_branch
'''
		
	}
	lock('my-resource-name') {
 
echo 'Finish'
	stage ('Docker Compose') {
		sh "sleep 30s"
  }}
	
	//Deploying/Downloading Artifacts to Artifactory and Build Promotions
	stage ('Deploy Artifacts') {
	
		}
	
	stage ('Email Notifications') {
		//notifySuccessful()
	}
}
