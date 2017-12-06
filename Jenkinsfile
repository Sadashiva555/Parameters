pipeline {
    agent any
    parameters {
        choice(choices: 'ENVIRONMENT', description: 'used for Posgress.sh and Code Deploymet Deploy Code', name: 'Environment')
        booleanParam(name: 'REBUILD_DATABASE',defaultValue: true,description: 'Should we re build the database?')
        booleanParam(name: 'DEPLOY',defaultValue: false,description: 'Should we deploy the application?')
        string (name: 'branch',defaultValue: 'Default',description: 'Select which branch you want to select?')
    }
        stages {
        stage('Example') {
            steps {
                echo "Hello ${params.ENVIRONMENT}"
            }
        }
    }
}
