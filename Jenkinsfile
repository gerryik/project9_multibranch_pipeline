pipeline{
  agent any 
  stages{
    stage('project9'){
      parallel{     
        stage('Gerald Agbonye'){
          when {
                branch 'feature'
            }
          steps{
            sh '/var/lib/jenkins/script/project9grp5q1scrpit.sh'
          }
        }
        stage('Pretei Lemo'){
          when {
                branch 'feature'
            }
          steps{
            echo "TODO"
          }
        }
   stage('Odile Domingo'){
    when {
           branch 'feature'
            }
       steps{
            echo "TODO"
        }
    }
  stage('Le Pere'){
    when {
           branch 'feature'
            }
       steps{
            echo "TODO"
        }
    }
        stage("Other Members") {
            when {
                not {
                    anyOf {
                        branch 'master';
                        branch 'develop';
                        branch 'feature'
                    }
                }
           }
           steps {
               echo "Other members not coming to group meetings"
            }
        } 
    stage('John Forsan'){
        when {
          branch 'feature'
            }
    	steps{
    		echo "TODO"
    	}
     }
    }
   }
  }
}

