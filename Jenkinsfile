node {
  stage('SCM Checkout'){
    git 'https://github.com/ataberkcil/JavaVulnerableLab'
  }
  stage('Build—Package'){
    def mvnHome = tool name: 'maven3', type: 'maven'
    sh "${mvnHome}/bin/mvn package"
    sh "wget https://github.com/kondukto-io/kdt/releases"
    sh "kdt-linux"
  }
}
