### Open Stack
---


- [### Open Stack](#-open-stack)
    - [Virtual Machine](#virtual-machine)
    - [Instance](#instance)
    - [Volume](#volume)
    - [Snapshop](#snapshop)
    - [Key Pair](#key-pair)
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
2. Attach the volume to the Instance:
   ```
    $ openstack server add volume machineName volumeName
   ```
3. 
  
#### Snapshop

#### Key Pair
* Create a Key Pair
* Use a Key Pair

