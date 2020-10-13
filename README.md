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
create new repository on your <a href="github.com">github</a> account.
<code><ol>
    <li>$ git init </li> 
    <li>$ git add .</li> 
    <li>$ git commit -m "first commit" .</li> 
   <li>$ git remote add origin https://github.com/yourname/yourrepositoryname.git </li> 
   <li>$ git branch -M master </li> 
    <li>$ git push -u origin master</li></ol>
</code> Now, refresh your respository page.

### Heroku deployment command
First you need Heroku account. if you not had heroku just go to the <a href="https://heroku.com">webiste</a>. and create a account.
Then type the following commands.
 <code>  <ol>
          <li>$ heroku login </li> 
         <li>$ heroku create <yourappname-It must be unique></li> 
         <li>$ git push heroku master</li> 
  </ol>
 </code>
 
 # Output
app is runing - <a href="https://cclabcloudapp.herokuapp.com/"> click me!</a>

##### If this project is useful for your, pur star to this respository.
