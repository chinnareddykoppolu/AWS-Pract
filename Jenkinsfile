pipeline {
    agent any
    parameters {
        gitParameter branchFilter: 'origin.*/(.*)', defaultValue: 'master', name: 'master', type: 'master'
    }
    stages {
        stage('AWS-Pract') {
            steps {
                git url: 'https://github.com/chinnareddykoppolu/AWS-Pract.git'
            }
        }
    }
}
