node {
  def SCM_URL="git@github.com:RichardWLaub/groovy-baby.git"
  def SCM_CRED_ID="github-cred" // SCM Credentials ID in Jenkins
    stage('pull code'){
      git credentialsId: SCM_CRED_ID, url: SCM_URL // get code from repo
    }
    stage('look at repo'){
      sh 'pwd; ls'
    }
}
