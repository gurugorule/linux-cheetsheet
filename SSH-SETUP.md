# how to setup ssh key in your Machine 
---
In your terminal type 
 * ssh-keygen -t ed25519 -C "your email"

- set the password and it will create .ssh file in /home/user dir 
- in .ssh dir your private and public key is saved 
 * don't share your private key 

copy your public key and go to github.com/settings/keys 
over there add your public ket 

Now in terminal type:
 * ssh-add 
- it will add ssh agent 

Now you are good to go 
- clone any repo vai ssh and push your code 
