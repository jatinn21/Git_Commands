<h1> Git For Cloning</h1>
<strong>_Clone_</strong> <br> Meaning : Cloning a repo on our local machine<br> in Hindi : koi bhi repo jo github pe hai, or hum usse apne system pe copy/duplicate karna chahte hai, use clone. <br>Code : git clone <-some link->

<strong>_Status_</strong> <br>Meaning : to check the status, is there any update in code? branch etc<br> in Hindi : kuch bhi change huva hai dekhna hai toh, use status.<br> Code : git status

//We have 4 types in status// <br>i. untracked : new files that git doesn't yet track <br>ii. modified : changed<br> iii. staged : file is ready to be commited, put in this status by using add command <br>iv. unmodified : unchanged

<strong>_Add_</strong> <br>
Meaning : adds new or changed files in your working directory to the git staging area<br> in Hindi : jo bhi changes ki hai ya koi new file create ki hai, usse staging ya track karna, using add <br>Code : git add <-file name-> (OR) git add . (when we have multiple files to put in staging area)

<strong>_Commit_</strong> <br>
Meaning : it is the record of change <br>in Hindi : kya commit ho raha hai, kya denote kya message hai?<br> Code : git commit -m "some message"

<strong>_Push_</strong><br>
Meaning : upload local repo content to remote repo (Github Repo) <br>in Hindi : yaha ke changes abh github pe reflect karenge<br> Code : git push origin main

<p>
Here git push is the command <br> 
<b>origin</b> : default name given to remote repo from which your local repo was cloned. It's essentially an alias for the URL of the remote repo.<br>
<b>main</b> : this is the name of the branch you are pushing to the remote repo. 
<p>
       
<i>Problems i have faced </i>:<br>
Question. If everything goes fine like push is reflecting in github but then you changed the github repo link then how to do push again in that repo?
Ans. <br><i>git remote set-url origin <- updated Link.git -></i><br>
then you can put this command : <i>git push origin main</i>
<br>

<h2>Git without cloning, Normal Way</h2>
i.<strong> <i>Create a empty folder</i></strong> <br>
 
ii. <strong> <i>git init</i></strong> <br>

iii.<strong> <i>git remote add origin <--git link--></i></strong> <br>
iv.<strong> <i>git remote -v</i></strong> <br>
Result : <br>
origin <--git link--> (fetch) <br>
origin <--git link--> (push)<br>
<br>
v.<strong> <i>git branch</i></strong> <br>
vi.<strong> <i>git branch -M main</i></strong> <br>
vii.<strong> <i>git status</i></strong> <br>
viii.<strong> <i>git add .</i></strong> <br>
ix.<strong> <i>git commit -m "enter message"</i></strong> <br>
x.<strong> <i>git push origin main</i></strong> <br>

<h2>That's It, We are done with this repo and git.</h2>
<img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExMDFpaWhla2pubmwxazJsb3c0NGZjdTQ2d3R2NXJwb3d5ZjNuZWJkbSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/mGK1g88HZRa2FlKGbz/giphy.gif" width="300">
