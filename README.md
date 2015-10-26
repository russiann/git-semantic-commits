## Installation:

1. Clone this repo, prefferably in your $HOME directory.
``` git clone https://github.com/russian60/git-semantic-commits ~/.git-semantic-commits ```

2. Add the folder to your $PATH.
  * if using Bash, open ```~/.bashrc``` with your favourite editor and add this line: <br/> ``` export PATH=$PATH:$HOME/.git-semantic-commits:$PATH ```
  * if using Zsh, open ```~/.zshrc``` with your favourite editor and add this line: <br/>  ``` export PATH=$PATH:$HOME/.git-semantic-commits:$PATH ```

3. Save the file and source the changes in bashrc/zshrc: ```source ~/.bashrc``` or ```source ~/.zshrc```
4. Done! grin emoticon

Commands:

* ```git feat "commit-message-here"```
* ---> ```git commit -m 'feat: commit-message-here'```
* ```git feat "component-name" "commit-message-here"```
* ---> ```git commit -m 'feat(component-name): commit-message-here'```
* ```git docs "commit-message-here"```
* ---> ```git commit -m 'docs: commit-message-here'```
* ```git docs "component-name" "commit-message-here"```
* ---> ```git commit -m 'docs(component-name): commit-message-here'```
* ```git chore "commit-message-here"```
* ---> ```git commit -m 'chore: commit-message-here'```
* ```git chore "component-name" "commit-message-here"```
* ---> ```git commit -m 'chore(component-name): commit-message-here'```
* ```git fix "commit-message-here"```
* ---> ```git commit -m 'fix: commit-message-here'```
* ```git fix "component-name" "commit-message-here"```
* ---> ```git commit -m 'fix(component-name): commit-message-here'```
* ```git refactor "commit-message-here"```
* ---> ```git commit -m 'refactor: commit-message-here'```
* ```git refactor "component-name" "commit-message-here"```
* ---> ```git commit -m 'refactor(component-name): commit-message-here'```
* ```git style "commit-message-here"```
* ---> ```git commit -m 'style: commit-message-here'```
* ```git style "component-name" "commit-message-here"```
* ---> ```git commit -m 'style(component-name): commit-message-here'```
* ```git test "commit-message-here"```
* ---> ```git commit -m 'test: commit-message-here'```
* ```git test "component-name" "commit-message-here"```
* ---> ```git commit -m 'test(component-name): commit-message-here'```
* ```git localize "commit-message-here"```
* ---> ```git commit -m 'localize: commit-message-here'```
* ```git localize "component-name" "commit-message-here"```
* ---> ```git commit -m 'localize(component-name): commit-message-here'```
