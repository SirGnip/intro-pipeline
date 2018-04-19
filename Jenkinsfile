pipeline {
  agent any
  libraries {
    lib("SharedLibs")
  }
  
  stages {
    stage('Say Hello') {
      steps {
        echo "Hello IN A BIG WAY ${MY_NAME}"
        sh "env -v"
      }
    }
    stage('Say Kernel') {
      steps {
        echo "${KERNEL_VERSION}"
      }
    }
  }
}
