# bsec
**/index.html**
<html>
<head><title>Team Portfolio</title></head>
<body>
  <h1>Welcome to Our Team Portfolio</h1>
  <p>Content will go here.</p>
</body>
</html>

**/styles.css**
body { font-family: Arial, sans-serif; background-color: #f0f0f0; } 
h1 { color: navy; }

**/script.js**
document.addEventListener('DOMContentLoaded', () => {
  alert('Welcome to the Team Portfolio!');
});

member2
**/index.html**
<html>
<head><title>Team Portfolio</title></head>
<body>
  <h1>Welcome to Our Team Portfolio</h1>
  <p>Content will go here.</p>
</body>
</html>

**/styles.css**
body { font-family: Arial, sans-serif; background-color: #f0f0f0; } 
h1 { color: navy; }

**/script.js**
document.addEventListener('DOMContentLoaded', () => {
  alert('Welcome to the Team Portfolio!');
});

member3
Index.html
<!DOCTYPE html>
<html>
<head>
  <title>Team Portfolio</title>
  <link rel="stylesheet" href="style.css"
</head>
<body>
  <header>
    <h1>Welcome to Our Team Portfolio</h1>
  </header>
  <section id="team">
    <h2>Meet the Team</h2>
    <div class="profile">
      <h3>Alice</h3>
      <p>Frontend Developer</p>
    </div>
    <div class="profile">
      <h3>Bob</h3>
      <p>UI/UX Designer</p>
    </div>
    <div class="profile">
      <h3>Charlie</h3>
      <p>JavaScript Developer</p>
    </div>
  </section>
  <footer>Contact us at: team@example.com</footer>
  <script src="script.js"> </script>
</body>
</html>

Script.js
document.querySelectorAll('.profile').forEach(profile => {
    profile.addEventListener('mouseenter', () => {
      profile.style.backgroundColor = '#f0f0f0';
    });
    profile.addEventListener('mouseleave', () => {
      profile.style.backgroundColor = 'white';
    });
  });

Style.css
body { font-family: Arial, sans-serif; margin: 0; padding: 0; }
header { background-color: #4CAF50; color: white; padding: 20px; text-align: center; }
.profile { margin: 20px; padding: 10px; border: 1px solid #ddd; }
footer { text-align: center; padding: 10px; background: #f1f1f1; }

Team leader	Team members
Go to githb.com and create a new repo
Create readme.md file and define  work to team members                                    
Go to settings and add collaborates
                1


Refresh github.com
Check pull request and you will observe new pull request and click on that
If there is conflict, resolve conflict
Otherwise click merge request
Confirm merge request

Team leader has to open terminal in vscode
  $ git init
$ git pull                             2
Run idex.html from vscode

                           3	Accept  request sent by team leader
Go to github and copy projrepolink(code)
Open vscode and terminal (git bash)
Enter  $ git init
Clone the repository sent by team leader using 
$ git clone  projrepolink
 $ls
cd projectrepo
switch to newbranch
Open a readme.md file according to the work assigned each team member has to create file (index.html/style.css/script.js)
Save the file,
Bring to staging area using
$git add .
Commit the file using
$git commit –m “suitable message”
Check remote origin using
$git remote –v
$git push origin newbranch
Goto github.com, refresh and create new pull request with appropriate message
  



Run index.html from vscode

