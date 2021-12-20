pipeline {
    agent any
    stages {
        stage ('Echo parameters') {
            steps {
                echo(GITHUB_URL)
                echo(TARGET_BRANCH)
                echo(SONAR_URL)
            }
        }
    }
}
