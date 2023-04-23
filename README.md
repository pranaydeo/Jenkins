 1. Install the necessary software on the machines using a configuration management tool. 
 2. Git Workflow has to be implemented 
 3. Code Build should automatically be triggered once commit is made to master branch or develop branch. If commit is made to master branch, test and push to prod If commit is made to develop branch, just test the product, do not push to prod 
4.  The Code should be containerized with the help of a Dockerfile. The Dockerfile should be built every time there is a push to Git-Hub. Use the following pre-built container for your application: hshar/webapp The code should reside in '/var/www/html'
5.  The above tasks should be defined in a Jenkins Pipeline, with the following Jobs 
    Job 1 - Building Website
    Job 2 - Testing Website 
    Job 3 - Push to Production
