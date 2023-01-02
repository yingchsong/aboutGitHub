# aboutGitHub

# How to connect local machine to github

Firstly, ssh:

cd ~/.ssh

ls

vi id_rsa.pub

// ctrl+a,ctrl+c

:q

Secondly, add ssh key in github

Thirdly, Creating a personal access token

Settings -> Developer settings -> Personal access tokens -> Generate new token -> Generate token

copy token and use following command:

git remote set-url origin  https://<your_token>@github.com/<USERNAME>/<REPO>.git

# clone and push

git clone <URL>

// see this tutorial:

//https://stackoverflow.com/questions/68775869/message-support-for-password-authentication-was-removed-please-use-a-personal

//after update

git add <fileName>

git commit -m 'comments'

git push
