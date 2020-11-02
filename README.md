# CEG3120
The repository used for CEG 3120 Design of Info Tech Systems.
<h1>Project 1</h1>
<h3>changelog:</h3>
<ul>
  <li>1.1 created the respository/script folder/and script project1.</li>
  <li>1.2 testing git commands and added echo hello world in project1</li>
  <li>1.3 Finished and pushed project1</li>
</ul>
<h1>Project 1-2</h1>
<h3>tasks and completion</h3>
<ul>
  <li>Created an issue in github for #4</li>
  <li>Fixed issue and closed the issue</li>
  <li>Created the git-guide.md and added information</li>
</ul>
<h1>Project 2-1 changelog:</h1>
<ui>
  <li>10/14/2020: Created VPC, default networking rules. VPC ID: vpc-066d75962e2d8ddcf</li>
  <br>

  <img src="https://github.com/NicholasChase/CEG3120/blob/master/img/VPC.PNG"><br>
  <li>10/16/2020: Edited Security Group, inbound rules, services to be traffic on 10.0.0.0/16</li><br>
  <img src="https://github.com/NicholasChase/CEG3120/blob/master/img/Security_Group1.PNG">
  <br>
  <li>10/26/2020: Learned we need to either use a t2.medium or AMI Ubuntu to fulfill gitlab server requirments.</li><br>
  <li>10/31/2020: Made a t2.medium instance</li>
  <img src="https://github.com/NicholasChase/CEG3120/blob/master/img/TC2_Creation.PNG"><br>
  <li>10/31/2020: Eddited security group, added WSU VPN Address and 0.0.0.0/0</li>
  <img src="https://github.com/NicholasChase/CEG3120/blob/master/img/Security_Group2.PNG">
  <li>11/1/2020: Eddited security group, added my IP Address allowed to ssh</li>
  <img src="https://github.com/NicholasChase/CEG3120/blob/master/img/Security_Group3.PNG">
  <li>11/1/2020: Learned I had made a major mistake and set the private key to a non useable key that I did not have access to. had to key the original t2.medium and make a new one :(</li>
  <img src="https://github.com/NicholasChase/CEG3120/blob/master/img/Goof.PNG">
  <li>11/1/2020: Successfully SSH into my new t2.medium, udated/upgraded/ rebooted, installed git, created a new user 'git'</li>
   <img src="https://github.com/NicholasChase/CEG3120/blob/master/img/gitUser.PNG">
   <li>11/1/2020: STUCK, I cannot get the git user to be able to ssh into the server</li>
   <img src="https://github.com/NicholasChase/CEG3120/blob/master/img/stuck.PNG">
   <li>11/2/2020: I have learned that I have made mistakes, my approach to the project is wrong and again will be going back and correcting where I have made mistakes</li>
   <li>11/2/2020: Created another instance and renamed the instances to GITserver and OpenLDAP and created two elastic IP's, they have been assigned to the appropiate instance</li>
   <img src="https://github.com/NicholasChase/CEG3120/blob/master/img/instances.PNG">
   <img src="https://github.com/NicholasChase/CEG3120/blob/master/img/ElasticIP.PNG">
   <li>11/2/2020: Configured the imbound rules. again...</li>
   <li>11/2/2020: switched the git server and the openldap server due to screwing up the settings with the git server </li>
   <li>11/2/2020: created a git project and initialized the git server</li>
    <img src="https://github.com/NicholasChase/CEG3120/blob/master/img/initial.PNG">
   <li>11/2/2020: started the OpenLDAP server, sudo apt-get install slapd ldap-utils, using guide: https://www.digitalocean.com/community/tutorials/how-to-install-and-configure-openldap-and-phpldapadmin-on-ubuntu-16-04</li>
    <img src="https://github.com/NicholasChase/CEG3120/blob/master/img/LDAP_install.PNG">
    <li>11/2/2020: Recondigured SLAPD and testing the connection of the OpenLDAP: Successs got the right output</li>
    <img src="https://github.com/NicholasChase/CEG3120/blob/master/img/reconfigSLAPD.PNG">
    
   
   
</ui>
