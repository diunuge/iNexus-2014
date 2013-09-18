//get the repository
git clone ssh://<user_name>@103.29.60.108:22/home/diunuge/git/redmine/iNexus2014.git

//set username and email
git config --global user.name "<user_name>"
// --global user.name "diunuge"
git config --global user.email "<user_email>"
// --global user.email "diunuge.10@cse.mrt.ac.lk"

//add/modify files
//create test file 
//ex: diunuge.txt and put something in it
echo 'test diunuge' --> diunuge.txt

git add <file_name>
// git add diunuge.txt

git commit -m "<Commit_Description>"
// git commit -m "Test Git Connection - Diunuge"

git remote add origin ssh://<user_name>@103.29.60.108:22/home/diunuge/git/redmine/iNexus2014.git
// git remote add origin ssh://diunuge@103.29.60.108:22/home/diunuge/git/redmine/iNexus2014.git

git push -u origin master



//get others changes/ syncronize with remote repository
git pull
