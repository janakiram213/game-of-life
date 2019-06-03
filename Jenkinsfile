node {
stage ('deploy to tomcat'){
      sshagent(['c56106af-f52f-418c-9462-1ab8a66fb8e3']) {
          sh 'scp -o StrictHostKeyChecking=no target/*.war jenkins@172.31.95.95:/opt/tomcat/webapps'
      }
    }
  } 
