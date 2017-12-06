pipeline {
    agent any
    parameters {
        string(name: 'PERSON', defaultValue: 'Mr Jenkins', description: 'Who should I say hello to?')
        booleanParam(defaultValue: false, description: '', name: 'foo')
if (params.foo) {
    echo "true: $foo"
}
else echo "false: $foo"
    }
    stages {
        stage('Example') {
            steps {
                echo "Hello ${params.PERSON}"
            }
        }
    }
}
