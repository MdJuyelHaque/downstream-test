// Powered by Infostretch 

timestamps {

node () {

	stage ('Job1 - Checkout') {
 	 checkout([$class: 'GitSCM', branches: [[name: '*/main']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'Mdjuyel', url: 'https://github.com/MdJuyelHaque/downstream-test']]]) 
	}
	stage ('Job1 - Build') {
 			// Shell build step
sh """ 
echo $Commit_id 
 """ 
	}
	stage ('job2 - Build') {
 			// Shell build step
sh """ 
echo $Commit_id 
 """ 
	}
}
}