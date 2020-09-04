node {
	timeout(time: 5 ,unit: 'SECONDS'){
	stage('build1') {
                 echo "Building C files ...."
		 sleep 6
              }
	}	
		stage('build2') {
                 echo "Building C++ files ...."            
        	}
		
		stage('build3') {
                 echo "Building Java files ...."
              }
  	 }

node {
        stage('test1') {
                 echo "Testing C files ...."
              }
		
		stage('test2') {
                 echo "Testing C++ files ...."            
        	}
		
		stage('test3') {
                 echo "Testing Java files ...."
              }
  	 }

node {
        stage('deploy1') {
                 echo "Deploying C files ...."
              }
		
		stage('deploy2') {
                 echo "Deploying C++ files ...."            
        	}
		
		stage('deploy3') {
                 echo "Deploying Java files ...."
              }
  	 }
