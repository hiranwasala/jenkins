pipeline {
    agent any
    stages {
        stage('Create Directory') {
            steps {
                script {
                    def dirName = 'new_directory'
                    sh "mkdir -p ${dirName}" // Create the directory
                    echo "Directory '${dirName}' created successfully."
                }
            }
        }
    }
}
