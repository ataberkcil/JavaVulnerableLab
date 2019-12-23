node {
  stage('SCM Checkout'){
    git 'https://github.com/ataberkcil/JavaVulnerableLab'
  }
  stage('Build—Package'){
    def mvmHome = tool name: 'maven3', type: 'maven'
    sh "${mvnHome}/bin/mvn package"
  }
}
