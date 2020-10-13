# cc lab cloudapp
## Pre-requirements
  1. Install <a href="https://git-scm.com/">git</a> on your system
  2. install <a href="https://www.python.org/">python 3.7</a> or higher version on your system.
  3. install Flask 1.12 
  4. install gunicorn == 20.0.4
 
### Flask installation command for linux
<code> pip install flask</code>

### Gunicorn installation command for linux
<code> pip install gunicorn</code>

### Git command to push your command on git
create new repository on your <a href="github.com">github</a> account.<br/>
<code> 1. git init<br/>
       2. git add .<br/>
       3. git commit -m "first commit" .<br/>
       4. git remote add origin https://github.com/yourname/yourrepositoryname.git <br/>
       5. git branch -M master <br/>
       6. git push -u origin master <br/>
</code><br> Now, refresh your respository page.

### Heroku deployment command
First you need Heroku account. if you not had heroku just go to the <a href="https://heroku.com">webiste</a>. and create a account.
Then type the following commands.
 <code>  1.  heroku login
         2. heroku create <yourappname-It must be unique>
         3. git push heroku master
 </code>

##### If this project is useful for your, pur star to this respository.
