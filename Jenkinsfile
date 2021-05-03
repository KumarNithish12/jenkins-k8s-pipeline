
pipeline {
agent any
  stages {
    stage('build') {
      steps {
        kubernetesDeploy(configs: "deploy.yml", kubeconfigId: "myk8sconfigfile")
      }
    }
  }
}
