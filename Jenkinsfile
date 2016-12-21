node {

  properties([
    pipelineTriggers([
      [$class: "GitHubPushTrigger"]
    ])
  ])

  stage('Build') {
    sh 'echo "Hello!"'
  }
  stage('Test') {
    sh 'echo "Test!"'
  }
}
