node {
	stage('Gitclone') {
	
		git credentialsId: '2ffd0121-8eab-4a99-adf6-8dcfacad0aa9', url: 'https://github.com/adityareddychowdari/jan2022.git'
	}
	stage('Maven version') {
		sh 'mvn -version'
	}
	stage('Java version') {
		sh 'java -version'
	}
	stage('Maven validate') {
		sh 'mvn -validate'
	}
	stage('Maven compile') {
		sh 'mvn compile'
	}
	stage('Maven Test') {
		sh 'mvn Test'
	}
	stage('Maven Package') {
		sh 'mvn Package'
	}
