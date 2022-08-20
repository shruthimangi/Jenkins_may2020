node {
    stage('Code Clone') {  
	   git 'https://github.com/shruthimangi/ks.git'
    }
	
	stage('Code Clean') { 
       
	   sh 'mvn clean'
    }
    stage('Maven Validate '){
	   sh 'mvn validate'
    }
    stage('Maven Compile') {
	   sh 'mvn compile'
	}
    stage('Maven Test') {
	
      sh 'mvn test'
	}
	stage('Maven Package') {
	
      sh 'mvn package'
}

	}
	