node{
  stage('SCM Checkout'){
    git 'https://github.com/sullururamesh/genkinsbuild'
  }
  echo 'Ramesh'
  stage('Compile-Package'){
  sh 'mvn package'
  }
}
