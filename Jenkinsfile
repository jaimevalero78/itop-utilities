node {
  try {
    stage('checkout') {
      checkout scm
    }
    stage('compile') {
      echo "nothing to compile for hello.sh..."
    }
    stage('test') {
       echo "test"
    }
    stage('package') {
      echo "test"
    }
    stage('publish') {
      echo "uploading package..."
    }
  } finally {
    stage('cleanup') {
      echo "doing some cleanup..."
    }
  }
}