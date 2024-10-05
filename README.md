Ansible Realtime Project

Task1 : 
- Create 3 EC2 instance on AWS using Ansible loop concept
   1. 2 instance with Ubuntu distribution 
   2. 1 instance with CentOs distribution

   Use: Connection: local as Ansible control node 

Task2 :
- Create passwordless authentication between Ansible control node and newly created instances

Task3 : 
- Automate shutdown ubuntu instances only using Ansible conditionals
  use: When condition on ansible gather_facts
