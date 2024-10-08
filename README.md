Ansible Realtime Project

Task1 : 
- Create 3 EC2 instances on AWS using the Ansible loop concept
   1. 2 instances with Ubuntu distribution 
   2. 1 instance with CentOs distribution

   Use: Connection: local as Ansible control node 

Task2 :
- Create passwordless authentication between the Ansible control node and newly created instances

Task3 : 
- Automate shutdown Ubuntu instances only using Ansible conditionals
  use: When condition on ansible gather_facts
