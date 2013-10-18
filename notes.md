##What we have done##

* First we configured a git repository and added us as collabrateurs
* We then pulled the repo each
* Edited the .gitconfig and .bashrc to get additional output
* Also we activated color in the output of git
* We went on to create merge-conflicts
* Next we forked the git repository of another group
* The git ssh-keys were added to our accounts, because retyping account-details every time is annoying

##Link Collection##
Add the ssh-keys to git-account
> https://help.github.com/articles/generating-ssh-keys

Add colorful graphs to your git-output
> http://stackoverflow.com/questions/1057564/pretty-git-branch-graphs

Add branch to your bash
* Copy .git-promt.sh to your computer
* Add the following to your .bashrc

>source $HOME/.git-script/.git-prompt.sh

>PS1="\t \u:\w\$(__git_ps1) >" 

* Thentype 'source .bashrc' and you should be done

worked together with Tu and Tim and forking repository MisterTu/LectureNotes . Then I changed the file alleskaputt.txt by adding a line of nonsense and sent them a pull request

Resolved a merge-conflict
