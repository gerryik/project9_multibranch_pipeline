pipeline{
  agent any 
  stages{
    stage('project9 Team5.group3:Pipeline'){
      parallel{     
        stage('Gerald Agbonye'){
          when {
                branch 'main'
            }
          steps{
            sh '/var/lib/jenkins/script/project9grp5q1scrpit.sh'
          }
        }
        stage('Pretei Lemo'){
          when {
                branch 'develop'
            }
          steps{
            echo "TODO"
          }
        }
   stage('Le Pere'){
    when {
           branch 'main'
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
    stage('Odile Domingo'){
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

