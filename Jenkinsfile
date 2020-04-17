pipeline {
    agent none
    parameters {
        string(name: 'commit_hash',)
    }

    stages {
        stage("Launch dummy pipeline") {
            agent any
            steps {
                script {
                    sh "echo ${params.commit_hash}"
                }
            }
        }
    }
}