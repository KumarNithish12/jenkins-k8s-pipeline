
pipeline {
agent any
  stages {
    stage('build') {
      steps {
        KubernetesDeploy(configs: "deploy.yml", kubeconfigId: "myk8sconfigfile")
      }
    }
  }
}
