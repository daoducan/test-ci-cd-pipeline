pipeline {
    agent {
        label "jenkins-agent"
    }
    environment {
        APP_NAME = "test-ci-cd-pipeline"
    }

    stages {
        stage("Cleanup Workspace") {
            steps {
                cleanWs()
            }
        }
    }
}
