# master
When we pull the repository branch master from remote "https://github.com/newhocsinh/master"
into this local /c/Users/Kent/master then we need to use these commands

% mkdir master
% cd master
% git init
% git pull origin master

After that we can modify file and push back to master branch
% vi README.md
<update, save, and exit file here>
% git status
% git add README.md
% git commit
% git push --set-upstream origin master
% git log
% git status

The new update of README.md file updates on the remote GITHUB web account
