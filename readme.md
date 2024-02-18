<strong>_Clone_</strong> <br> Meaning : Cloning a repo on our local machine<br> in Hindi : koi bhi repo jo github pe hai, or hum usse apne system pe copy/duplicate karna chahte hai, use clone. <br>Code : git clone <-some link->

<strong>_Status_</strong> <br>Meaning : to check the status, is there any update in code? branch etc<br> in Hindi : kuch bhi change huva hai dekhna hai toh, use status.<br> Code : git status

//We have 4 types in status// <br>i. untracked : new files that git doesn't yet track <br>ii. modified : changed<br> iii. staged : file is ready to be commited, put in this status by using add command <br>iv. unmodified : unchanged

<strong>_Add_</strong> <br>
Meaning : adds new or changed files in your working directory to the git staging area<br> in Hindi : jo bhi changes ki hai ya koi new file create ki hai, usse staging ya track karna, using add <br>Code : git add <-file name-> (OR) git add . (when we have multiple files to put in staging area)

<strong>_Commit_</strong> <br>
Meaning : it is the record of change <br>in Hindi : kya commit ho raha hai, kya denote kya message hai?<br> Code : git commit -m "some message"

<strong>_Push_</strong><br>
Meaning : upload local repo content to remote repo (Github Repo) <br>in Hindi : yaha ke changes abh github pe reflect karenge<br> Code : git push origin main

<i>Problems i have faced </i>:<br>
Question. If everything goes fine like push is reflecting in github but then you changed the github repo link then how to do push again in that repo?
Ans. <br><i>git remote set-url origin <- updated Link.git -></i>
then you can put this command : <i>git push origin main</i>
<br>
