pipeline {
    agent any
    parameters {
        string(name: 'ENVIRONMENT', defaultValue: 'Integration', description: 'used for Posgress.sh and Code Deploymet Deploy Code')
        string(name: 'branch', defaultValue: 'Default', description: 'Select which branch you want to select?')
    }
        stages {
        stage('Example') {
            steps {
                echo "Hello ${params.PERSON}"
            }
        }
    }
}
