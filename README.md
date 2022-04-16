pipeline{
       agent any
       stages{
             stage ('build'){
                       steps{
                           echo " hello wrold"
                           stage ('test'){
                                  steps{
                                  
                                  
                                  }
                           
                           }
                       
                       }
             
             }
       
       }
       
         

}
