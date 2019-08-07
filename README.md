# ansible-ruby

## How to use Playbook:

* <b>Clone Repository:</b> 
  <pre><code>git clone https://github.com/ohiodn8/ansible-ruby.git</code></pre>
  
* <b>cd into repo folder:</b>
  <pre><code>cd ansible-ruby</code></pre>
  
* <b>Edit the hosts file in the folder to your liking. As it is, it'll install Ruby on localhost.</b>  
  
* <b>Run Playbook:</b>
  <pre><code>ansible-playbook playbook.yml</code></pre>



## Ansible Playbook to Install RVM and Ruby (on Debian & Ubuntu);; Epel, RVM & Ruby (on Amazon Linux & CentOS)

* This playbook will install rvm, ruby, nodejs and bundler gem to debian and ubuntu. (The same thing for amazon linux and centos, but an addition of epel-release).

* (To run the playbook, the playbook has to be in /home/[user], otherwise change the path in ansible.cfg e.g. ~/ansible-ruby)

* Do not follow the ansible installation steps below; it'll work for ubuntu only. Head over to ansible documentation page for the other OSs.

* <b>Install Ansible on Ubuntu Server: </b>
  <pre><code>sudo apt-get install software-properties-common && sudo apt-add-repository ppa:ansible/ansible && sudo apt-get update && sudo apt-get install ansible</code></pre>
