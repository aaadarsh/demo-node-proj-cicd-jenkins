//---------- creating a remote repo on git ----------------

git init                                    //initiate git in the app folder 

git add .                                   //add the the files for tracking 

git commit -m 'add commit msg'              //add commit message, now these files are in the staged form, ready to be pushed to remote repo

git remote add origin <github repo link>    //add the remote repo to the local folder

git push -u origin master                   //push the commits to the master/main branch of the remote repo 


//----------- joining a new project -----------------------

git clone <remote repo link>                //clone the remote repo locally 

git pull                                    //pull the latest changes

git checkout -b <branch name>               //create your own branch 

git add .                                   //add the the files for tracking 

git commit -m 'add commit msg'              //add commit message, now these files are in the staged form, ready to be pushed to remote repo

git push -u origin master                   //push the commits to the master/main branch of the remote repo 


