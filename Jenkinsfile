pipeline {
agent { slave-1 { label 'slave-1' } }
 stages {
      stage ('build docker file') {
         steps {
             sh 'mkdir -p /arpan'
             sh 'cd /vikash'
             sh 'docker build -t tomcat-server -f image-build'
}
  }
    }
