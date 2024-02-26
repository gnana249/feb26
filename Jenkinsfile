pipeline 
     {
      agent any
      stages
      {
       stage('git')
       {
        steps
            {
              git "https://github.com/gnana249/feb26.git"
              }
}
        stage('run')
        {
         steps
            {
             sh "java demo.java"
             sh "python3 main.py"
             }
        }
       
      }//stages
      }//pipelin
