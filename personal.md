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