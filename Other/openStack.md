### Open Stack
---


- [### Open Stack](#-open-stack)
    - [Virtual Machine](#virtual-machine)
    - [Instance](#instance)
    - [Volume](#volume)
    - [Snapshop](#snapshop)
    - [Key Pair](#key-pair)
    - [Notes:](#notes)
---

#### Virtual Machine
* Flavor

#### Instance
* Create Instance (VM)
  
#### Volume
* What is a Volume
* Why to use Volumes in VM
* Create Volume
  
1. Create the volume with size in GB:
    ```
    openstack volume create --description "Volume for documentation" --size 10 volumeName
    ```
    Optional parameters:
    - --size: size in GB of the volume to be created
    - --type: in our case io1
    - --description: text description of the volume.
2. Attach the volume to the Instance:
   ```
    $ openstack server add volume machineName volumeName
   ```
3. 
  
#### Snapshop

#### Key Pair
* Create a Key Pair
* Use a Key Pair

#### Notes:
* When using OpenStack on the terminal it needs to be accessed:
  * First, with the rigth permits. For example a VM or a Volume can not be cerated with lxplus or lxplus8 logIn but it can be done with aiadm logIn.
  * When using OpenStack in the terminal we need to access the right server: `$ eval $(ai -rc "it hadoop service development)`