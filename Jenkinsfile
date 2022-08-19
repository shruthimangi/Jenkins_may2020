node {
    stages('Code Clean') {
	    
		sh 'mvn clean'
	}
    stage('Code Clone') {  
	   git branch: 'main', url: 'https://github.com/shruthimangi/ks.git'
    }
    stage('Maven Validate ') {
	
	   sh 'mvn Validate'
    }
    stage('Maven Compile') {
	
	   sh 'mvn Compile'
	}
    stage('Maven Test') {
	
	   sh 'mvn Test'
	}
	stage('Maven Package') {
	
	   sh 'mvn Package'
}

	}
	