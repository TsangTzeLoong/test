## Win command list: 
> open path: 

__start .__

> change disk

__disk:__

## Generate & add ssh public key: 
1. check first with: ls ~/.ssh/
> // -t is kinda safe method, -C is optional for recognition
2. generate one with: ssh-keygen -t ed25519 -C "your_email@example.com"
3. copy public key with: cat ~/.ssh/id_ed25519.pub (Mac & Linux)

## Git delete remote branch:
1. how to add a same name remote branch:
* git push -u origin \<local branch name> 
> branch name no need to add "remotes" or "origin"
2. how to delete remote branch:
* git push origin :\<remote branch name>
3. how to relate local branch to remote branch:
* git branch -u  origin/\<remote branch name>
> can new a local branch and relate to remote one
* git checkout -b \<local branch name> \<remote branch name>