**August 3, 2022**
* Learn the command ksu to access VMs.
* When using OpenStack we need to evaluate or acess the right enviroment. For example `eval $(ai -rc "it hadoop service development)`.
* How to create and attach volumes in the command line on OpenStack:
  * Create a volume: `$ openstack volume create volumeName`.
  * Attach Volume: `$ openstack server add volume serverName volumeName`.
* How to do git commit and push on the command line.
* How to install Hadoop and set up enviroment: [tutorial](https://www.guru99.com/how-to-install-hadoop.html#1) 
* . is the same as source in cmd (wtf)

**August 5, 2022**
* `ksu` kerberized super-user
* `doAs` is a minimalistic alternative to `sudo` that allows you to run commands as another user.
* Learn ACLs