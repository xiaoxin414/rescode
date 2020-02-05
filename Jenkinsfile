pipeline {
    agent any
    parameters {
        string(name: 'Hi', defaultValue: 'Hello', description: 'How should I greet the world?')
    }
    stages {
        stage('Example') {
            steps {
                echo "${params.Hi} World!"
            }
        }
    }
}
