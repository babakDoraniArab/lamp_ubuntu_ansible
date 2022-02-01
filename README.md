### Run LAMP with Ansible on Ubuntu 18.4
if you want to run lamp on ubuntu first you need to install some packages. then you need to configure Apache and create document root.

after basic installation you have to configure MySql and Apache  and Uncomplicated Firewall

then just copy the info.php page and reload Apache and it's all set

if you have ec2 and pem file, you have to configure your ssh config to connect easily also I have to say I have ec2 and below configuration is added to ‍`~/.ssh/config` so you can do it too.

`Host ec2`

`  Hostname ec2-34-250-162-119.eu-west-1.compute.amazonaws.com`

  `user ubuntu`
  
  `IdentityFile ~/Downloads/Demo.pem`
  