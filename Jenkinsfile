
pipeline {
agent any
  stages {
    stage('build') {
      steps {
        sh "kubectl apply -f deploy.yml --kubeconfig admin.conf"
      }
    }
  }
}
