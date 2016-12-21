node {
  stage('Build') {
    sh 'echo "Hey!"'
  }
  stage('Test') {
    sh 'echo "Test!"'
  }
  stage('Trigger') {
    build "agg/${BRANCH_NAME}"
  }
}
