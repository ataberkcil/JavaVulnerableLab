node {
  stage('SCM Checkout'){
    git 'https://github.com/ataberkcil/JavaVulnerableLab'
  }
  stage('Build—Package'){
    sh 'mvn package'
  }
}
