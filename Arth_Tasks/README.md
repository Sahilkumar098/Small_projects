# Arth_Task_and__Learning
[X] Task 10

π°Write an Ansible PlayBook that does the
following operations in the managed nodes:

πΉ Configure Docker

πΉ Start and enable Docker services

πΉ Pull the httpd server image from the Docker Hub

πΉ Run the docker container and expose it to the public

πΉ Copy the html code in /var/www/html directory and start the web server


[ ] Task 11

π° 11.1 Configure Hadoop and start cluster
services using Ansible Playbook

π° 11.2 Create a Article, blog or Video on how
industries are solving challenges using Ansible.

π° 11.3 Restarting HTTPD Service is not
idempotence in nature and also consume more
resources suggest a way to rectify this challenge
in Ansible playbook

[ ] Task 12

12.1 Use Ansible playbook to Configure Reverse
Proxy i.e. Haproxy and update it's configuration
file automatically on each time new Managed node
(Configured With Apache Webserver) join the inventory.

12.2 Configure the same setup as 12.1 over AWS
using instance over there.


[ ] Task 15

πCreate an ansible role myapache to configure Httpd WebServer.

πCreate another ansible role myloadbalancer to configure HAProxy LB.

πWe need to combine both of these roles controlling webserver versions
and solving challenge for host ip's addition dynamically over each Managed
Node in HAProxy.cfg file.

[ ] Task 19

π Ansible Role to Configure K8S Multi Node Cluster over AWS Cloud.

π Create Ansible Playbook to launch 3 AWS EC2 Instance

π Create Ansible Playbook to configure Docker over those instances.

π Create Playbook to configure K8S Master, K8S Worker Nodes on the above created EC2 Instances using kubeadm.

π Convert Playbook into roles and Upload those role on your Ansible Galaxy.

π Also Upload all the YAML code over your GitHub Repository.

π Create a README.md document using markdown language describing your Task in creative manner.

π Create blog about task and share on your LinkedIN profile.
