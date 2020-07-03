node() {
    stage('Checkout') {
        git "https://github.com/Mihailov-SA/test_jenkins.git"
        deleteDir() // Workdir cleanup
    }

    stage('Build') {
        sh "echo Building"
        sh "echo 'Change Jenkinsfile'"
    }

    stage('Tests') {
        sh "echo Testing"
    }

    stage('Push image') {
        sh "echo Pushing"
    }
}
