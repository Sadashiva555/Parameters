pipeline {
    agent any
    parameters {
        choice (name: 'ENVIRONMENT',      defaultValue: 'Integration',  description: 'used for Posgress.sh and Code Deploymet Deploy Code')
        boolean(name: 'REBUILD_DATABASE', defaultValue: 'true',     description: 'Should we re build the database?')
        boolean(name: 'DEPLOY',           defaultValue: 'false',     descriptin: 'Should we deploy the application?')
        string (name: 'branch',           defaultValue: 'Default',      description: 'Select which branch you want to select?')
    }
        stages {
        stage('Example') {
            steps {
                echo "Hello ${params.PERSON}"
            }
        }
    }
}
