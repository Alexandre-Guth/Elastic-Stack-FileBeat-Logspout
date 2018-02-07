# Elastic-Stack-FileBeat-Logspout
On behalf of my employer [Phospore SI](https://www.phosphore.eu/), I deployed an **Elastic Stack** within a **Rancher** environment using **FileBeat** and **Logspout** as log shippers. Here is the documentation I pulled out from my work.

### What you'll find here

All the different configurations files for the softwares we deployed plus a [wiki](https://github.com/Alexandre-Guth/Elastic-Stack-FileBeat-Logspout/wiki) with instructions.
I highly recommend to have a look at the attached [wiki](https://github.com/Alexandre-Guth/Elastic-Stack-FileBeat-Logspout/wiki) before starting deploying and of course the [official documentation](https://www.elastic.co/guide/index.html).

We deployed the Elastic Stack on a single node to start with and do our test. In production, we will deploy a 3 nodes Elastic cluster.
ELK aka Elasticsearch-Logstash-Kibana is evolving fast, we deployed a 6.0.1 Elastic Stack but les than 2 months later, ELK is already hitting the 6.2 version. However the set up displayed in this repository will be good to go hopefully for a while since the major evolution was from 5.0 to 6.0. 

We deployed our Elastic Stack in a Rancher environment but this documentation can be used in any environment involving Docker containers. We work with Ubuntu servers so all the commands you will find here are deb.

### Prerequisites

To achieve an Elastic Stack deployment, you will need knowledge in the following:

#### Mandatory
* Docker
* Docker Compose

#### It helps
* Java
* JSON
* Rancher
* RegEx

### How to use it

1. Read the [wiki](https://github.com/Alexandre-Guth/Elastic-Stack-FileBeat-Logspout/wiki) first
2. Pay attention to the [prerequisites](https://github.com/Alexandre-Guth/Elastic-Stack-FileBeat-Logspout/wiki/2.-Prerequisites)
3. Check the [official documentation](https://www.elastic.co/guide/index.html)
4. Prepare a lot of coffee
5. Deploy!

**Please feel free to ask questions, make comments or suggestions to improve this repository**
