
pipeline {
agent any
  stages {
    stage('build') {
      steps {
        sh "sudo kubectl apply -f deploy.yml --kubeconfig /root/admin.conf"
      }
    }
  }
}
