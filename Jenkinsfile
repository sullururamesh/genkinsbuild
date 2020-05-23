node{
  stage('SCM Checkout'){
    git 'https://github.com/sullururamesh/genkinsbuild'
  }
  stage('Compile-Package'){
  sh 'mvn package'
  }
}
