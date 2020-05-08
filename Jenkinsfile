pipeline {
    agent any 
	parameters{
	string(name: 'userName' defaultValue: 'youku' description: 'my name is youkudiss')
	booleanParam(name: 'isSex' defaultValue: '男' description: '性别默认男')
	choice(name: 'version', choices: ['1.1', '1.2', '1.3'], description: 'select the version to test')
	}
    stages {
        stage('Build') { 
            steps {
                println "Build" 
            }
        }
        stage('Test') { 
            steps {
                println "Test" 
            }
        }
        stage('Deploy') { 
            steps {
                println "Deploy" 
            }
        }
    }
}
