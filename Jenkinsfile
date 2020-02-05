def username = 'xiaoxin'

node {
    stage('build-using-scm'){
     echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
    }
    
    stage('test-using-scm'){
     echo "I said, Hello Mr. ${username}"
    }
    
    stage('deploy-using-scm'){
     echo 'deploy';
    }
}