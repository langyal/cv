## 2023-present: E2E design for different TELCO companies within Deutsche Telekom
- creating *solutions* for our customers
- combining our flagship products: IaaS (VMs based on Openstack), CaaS (containers based on Kubernetes) and STaaS (storage based on Ceph)
- adding *automation* (Gitops principles) to the solutions (Gitlab pipelines, Flux, Argo CD)
- extending our product portfolio based on the requirements (e.g. object storage, global load balancer, etc.)

## 2018-2023: Product Owner for IaaS (Openstack)
- I was driving the development of the next release called Beryllium
  - Openstack next release
  - based on still Contrail but combined with SmartNICs from Netronome for packet offloading
  - see my [presentation](https://youtu.be/UUDUchhnxHY?si=WKAxZBTSh7Y1PJRS) on the Openstack Summit in Denver, 2019
- I was driving the development of the next release called Boron
  - Openstack next release
  - new underlay network design
  - eliminating Contrail and SmartNICs, using just OVS and SR-IOV
- I was driving the development of the next release called Carbon
  - Openstack next release
  - in-place upgrade from the previous release, including
    - operating system upgrade
    - Openstack upgrade
    - OVS to OVN migration

## 2015-2018: Pioneering the cloud domain in Pan-Net, a Deutsche Telekom spin-off company
- we were handled as a startup within DT
- we had to design, build and operate a private cloud based on opensource solutions
- we cooperated with different vendors:
  - Lenovo/HPE for the servers
  - Juniper for the network devices and for their SDN Contrail
  - Canonical for Openstack
- the outcome was our first release called Lithium

## 2015: Migration of the IT workload of RWE Hungary from one provider (IBM) to the other (T-Systems Hungary)
- that was a 9 months long project
- we used various technologies for the migration: storage synchronization, VM migration (VMware) and IBM POWER based workload migration
- we had to keep the applications running as long as possible
- we had to migrate the network, including firewalls, routers, remote device management

## 2013: Budapest Bank, Solaris virtualization
- the bank was forced to run a legacy application
- all they had a backup of the application on a Solaris 8 based installation
- we had to run the application on a modern hardware that obviously did not support Solaris 8 any more
- the solution was to install Solaris 11, integrate the system with a SAN based Hitachi storage and set up storage replication between two sites
- next, we configured LDOM (Logical Domains, like IBM's LPAR) with Solaris 10
- next, we restored the backup into a so called Solaris 8 branded zone (early containers on SPARC) and we could successfully run the system
- actually, this was a one man show, so I could replace "we" with "I" above

## 1994-2013: working for more than 120 different companies in Hungary
- system integration based on various technologies: Solaris/SPARC, IBM/POWER, HPUX/PA-RISC, VMware
- firewall design and integration with proxy based and stateful packet filtering solutions (Checkpoint FW-1)
- editing sendmail.cf configuration with vi (this is not a joke, that was my first real added value in 1994 for my company)

