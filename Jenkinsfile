pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                 nodejs(nodeJSInstallationName: 'Node 18.x', configId: '<config-file-provider-id>'){
                    sh 'npm install' 
                 }
            }
        }
    }
}