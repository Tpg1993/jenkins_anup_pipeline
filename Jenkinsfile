pipeline {
    agent any

    stages {
        stage('Print Branch Name') {
            steps {
                script {
                    // Get the branch name from the environment variable
                    def branchName = env.BRANCH_NAME
                    echo "Hello, ${branchName}"
                }
            }
        }
    }
}
