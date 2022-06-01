# ec2-KeytoPassword
# On target machine
1) sudo vi /etc/ssh/sshd_config
   - uncomment PasswordAuthentication yes
   - uncomment PermitRootLogin yes

2) sudo passwd ec2-user
   - specify password

3) sudo service sshd restart

# On controller,
   ssh ec2-user@ip
   - password
   
