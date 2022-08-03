

  - [Block vs. Object Storage](#block-vs-object-storage)
    - [Storage](#storage)
    - [Block Storage](#block-storage)
    - [Object Storage](#object-storage)
    - [Comparison](#comparison)
  - [section 2](#section-2)
  - [section 3](#section-3)

# Concepts Apache Ozone and Related

## Block vs. Object Storage

### Storage

Component in a machine that ensures that stores data in the long-term basis. It ensures that the data needed to be access by other components, services and applications can be retrieve any time. Different **System Storage** can be used to archive data. The main System Storages are File Storage, Bock Storage and Object Storage. Each one of them hold, organizes and presents data in different ways.

### Block Storage
Block storage chops data into blocks and stores them in separates pieces. It gives each piece a uniquely identifier what allows to store the data wherever is most convinient. That means for example a piece of data can be stores in a Linux machine and another in a Windows machine.

One of teh main purpose of object storage is to decouple the data from the server enviroment and spread it amoung several enviroments. Block storage does not depend on a single path of data (like file system) so it can be retrieved quickly. It performs well for huge data bases.

Some downsides is that object storage 


### Object Storage
### Comparison

## section 2

## section 3

## References
* [File, Block, Object Storage overview](https://www.redhat.com/en/topics/data-storage/file-block-object-storage)
* 