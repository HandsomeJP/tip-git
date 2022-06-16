# Windows

## Generate ssh key with your github email
`ssh-keygen -t ed25519 -C [email]`

## Generating public/private ed25519 key pair.
Enter file in which to save the key (C:\Users\Administrator/.ssh/id_ed25519): `You can just move to next step by click Enter`

Enter passphrase (empty for no passphrase): `Enter`

Enter same passphrase again: `Enter`

## SSH key generated
Your identification has been saved in C:/Users/[User Name]/.ssh/id_ed25519.
Your public key has been saved in C:/Users/[User Name]/.ssh/id_ed25519.pub.

## Set ssh key for github
https://github.com/settings/ssh/new

(Settings -> SSH and GPG keys -> New SSH key)

Copy your key string from id_ed25519.pub and paste on github.
