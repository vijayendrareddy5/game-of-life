node{

     stage('SCM'){
	 
	       git 'https://github.com/vijayendrareddy5/game-of-life.git'

	 }
	 stage('maven package'){
	 
	       sh 'mvn package'

	 }
	 stage('Archive the .exec files'){
	 
	         archive 'target/*.exec'

	 }

}
