# creating new GitHub repository from cmd line

Steps:
mkdir git-create-test
cd git-create-test/
git init
echo "# creating new GitHub repository from cmd line" >> README.md
git add README.md
git commit -m "initial commit"
curl -u 'sbalsky' https://api.github.com/user/repos -d '{"name":"git-create-test"}'
git remote add origin https://github.com/sbalsky/git-create-test.git
git push -u origin master

# updating GitHub file from local file
