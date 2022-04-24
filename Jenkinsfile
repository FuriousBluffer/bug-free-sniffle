pipeline {
  agent any
  stages {
    stage("Testing") {
      steps {
        echo "running super tests"
        bat "mvn test"
      }
    }
    stage("Build") {
      steps {
        echo "building it up"
        bat "mvn package"
      }
    }
  }
}
