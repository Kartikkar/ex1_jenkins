pipeline {
agent any
stages { 
stage('checkout') {
steps { 
echo "welcome"
}
  stage('build') {
    steps {
      "mvn clean package"
        }
  }
}
}
}
