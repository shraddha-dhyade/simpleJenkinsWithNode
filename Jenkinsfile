pipeline {
	agent any	
	tools {nodejs "my-node"}	
	stages {
		stage("Check Node Version"){
			steps {
				sh "node --version"
}
}
		stage("Install dependencies"){
			steps {
				sh "npm --version"
				sh "npm install"
}
}
		stage("Test"){
			steps {
				sh "node app.js"
}
}
		stage("Release the version"){
			steps {
				echo "Release the Version"
}
}
}
}
