# git-create-test

<b>Creating a new GitHub repository from the command line: </b>
<div>
<dl>
  <dt>Steps:
    <dd>mkdir git-create-test
    <dd>cd git-create-test/
    <dd>git init
    <dd>echo "# creating new GitHub repository from cmd line" >> README.md
    <dd>git add README.md
    <dd>git commit -m "initial commit"
    <dd>curl -u 'sbalsky' https://api.github.com/user/repos -d '{"name":"git-create-test"}'
    <dd>git remote add origin https://github.com/sbalsky/git-create-test.git
    <dd>git push -u origin master
  </dt>
</dl>
<br><br>

<b>Updating GitHub file with local file: </b>
<div>
<dl>
  <dt>Steps:
  <dd>
  </dt>
</dl>
