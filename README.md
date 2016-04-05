# ansible-openvpn
ansible playbook for openvpn server along with shell script

#ansible playbook for openvpn on aws vps
Please modify the following things for the above mentioned post:

– Open the UDP port 1194 inside the NAT instance Security Group

– Allow the desired traffic inside the desired desination server(s) Security Group for NAT instance

Edit the variable file **aws_openvpn/vars/main.yml** as per your requirement,

Edit **host** file:-

command to run:-
       
       ansible-playbook -i hosts site.yml
       
       

##### It create a **client** directory inside your repository from where yuo run playbook inside that your .ovpn keys are save use to login for openvpm
