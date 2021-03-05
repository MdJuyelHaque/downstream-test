// Powered by Infostretch 

timestamps {

node () {

	stage ('job3 - Checkout') {
 	 checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'Mdjuyel', url: 'https://github.com/MdJuyelHaque/downstream-test']]]) 
	}
	stage ('job3 - Build') {
 			// Shell build step
sh """ 
echo $test 
 """ 
	}
	stage ('job2 - Build') {
 			// Shell build step
sh """ 
echo $test 
 """ 
	}
}
}