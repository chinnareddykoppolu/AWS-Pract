pipeline {
    agent any
    parameters {
        gitParameter branchFilter: 'origin.*/(.*)', defaultValue: 'master'
    }
    stages {
        stage('AWS-Pract') {
            steps {
                git branch: "${params.master}", url: 'https://github.com/chinnareddykoppolu/AWS-Pract.git'
                
            }
        }
    }
}
