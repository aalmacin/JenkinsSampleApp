node {
  stage('Build') {
    withDockerContainer(image: 'node:8.11.4', toolName: 'docker') {
      sh 'npm install'
    }
  }
}
