pipeline {
  agent any
  stages {
    stage("Testing") {
      steps {
        echo "running super tests"
        sh "mvn test"
      }
    }
    stage("Build") {
      steps {
        echo "building it up"
        sh "mvn package"
      }
    }
  }
}
