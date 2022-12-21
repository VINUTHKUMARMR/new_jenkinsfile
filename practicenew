pipeline{
stages{
parallel{
stage('BUILD') {
      steps {
        echo "Deploying to ${params.ENV}"
        echo "Code from ${params.BRANCH} branch"
        sh '''
              echo Deploying to ${BRANCH}
              echo Code from ${ENV} branch
              exit 0
           '''
      }
    }
    
    stage('test') {
      steps {
        echo "Deploying to ${params.ENV}"
        echo "Code from ${params.BRANCH} branch"
        sh '''
              echo Deploying to ${BRANCH}
              echo Code from ${ENV} branch
              exit 0
           '''
      }
    }
    }
  }
}
