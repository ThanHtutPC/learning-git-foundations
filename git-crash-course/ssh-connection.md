## create the directory for ssh

```sh
mkdir ssh-connection-exercies
cd ssh-connection-exercises
```

## git init and git clone remote url 

```sh 
git init 
git clone git@github.com:ThanHtutPC/learning-git-foundations.git
```

## ssh connection with git and local server

```sh
ssh-keygen -t rsa -b 2048 --> (create the file name )
cat ~/.ssh/git-connection (copy output)
eval "$(ssh-agent -s)"
ssh-add [path-to-private-key]
```
## add the key in github 

```md
https://github.com/settings/keys

add the key in the New SSH key
```

## verify the ssh connection with git

```sh
ssh -T git@github.com
```
Than you can push with `git push` command. 

```sh 
git push <git-ssh-url>
```