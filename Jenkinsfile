node {
  
  properties([
    pipelineTriggers([
      [$class: "GitHubPushTrigger"]
    ])
  ])

  stage('Build') {
    sh 'echo "Hey!"'
  }
  stage('Test') {
    sh 'echo "Test!"'
  }
}
