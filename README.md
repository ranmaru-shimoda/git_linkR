# git_linkR
How to connect use Rstudio and Github

Create ssh key in terminal
  ssh -keygen
  
Copy it using the code below and paste it to new github/setting/SSH and GPG keys page
  pbcopy < ~/.ssh/id_rsa.pub


Type ssh -T git@github.com onto Rstudio and it should automatically connect to github. 
