node
{
  stage('SCM checkout'){
    git 'https://github.com/chandumanu111/mavenTest'
  }
  stage('Compile-package')
  {
    sh 'mvn package'
  }
}
