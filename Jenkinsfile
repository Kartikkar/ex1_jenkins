pipeline {
agent any
stages { 
stage('checkout') {
steps { 
sh "touch 2.txt"
}
}
  stage('build') {
    steps {
      "vi 2.txt"
      "Welcome"
    }
  }
}
}
