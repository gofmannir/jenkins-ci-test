node('master') { 
	checkout scm 
	stage('build') {
		withMaven(jdk: 'Default java', maven: 'Default maven') {
			sh 'mvn clean install' 
		}
	} 
}
