# how to setup ssh key in your Machine 

``` bash
ssh-keygen -t ed25519 -C "your email"
```

Set the password and it will create .ssh file in home dir, your private and public key is saved in .shh

```bash
eval "$(ssh-agent -s)"

ssh-add ~/.ssh/id_ed25519
# it will add ssh agent 
```
add your public SSH key to GitHub 
Now you are good to go! Clone any repo vai ssh and push your code 

> [!WARNING]
> Do not Share your private key 
