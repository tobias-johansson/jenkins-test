node {
  stage('Build') {
    sh 'echo "Hey!"'
  }
  stage('Test') {
    sh 'echo "Test!"'
  }
  build: 'agg/$BRANCH_NAME'
}
