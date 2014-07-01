# Day 1
-----
## Virtual Systems
Requirements:

Manageable:

Non-manageable:


performance issues

products

Can   virtualize memory (RAM)
          Storage (storage network)
          Consolidation of servers


things that can happen:
physical server goes down, network link can go down - both result in a down virtual server.

QNX real time linux



BRIDGED mode root the vm nic into the hardware nic

NAT network address translation

Server Farming people who operate a data center in the name of a company. provide power,  staff, matanence 24/7 ( Physical Servers )

Goes together with cloud computing. (Virtual Server)
## Cloud Computing Concepts
----
ICT - capital, how much should you need for a startup

Capital - equipment, machines, need to acquire. CAPEX

Operational - staffing, elect. internet, software licensing, repairs, insurance - OPEX

Total cost of ownership TCO

CAPEX + OPEX = TCO

No one size fits all due to high variance.

Busy Hour - typical peaks in usage of a system

Idea is to offer out unused data centers to make up for losses in cloud computing usage.

CC has elasticity.

CC is more of a economical saving then a technical advance.

on demand
broad network access
resouces poolling
rapid elasticty
pay as you go ( metered service)

network compute storage virtualization

MAIN IDEA - infrastructure as a service IAAS

software as a service SAAS

platform as a servive PASS

Deploment models

public cloud
private cloud
hybrid cloud
community cloud

-------
# Day 2
-------
## OpenStack

O.S. provides compute network and storage and shared services(support)

each service is separate

-----
NOVA
Nova does the computing of OpenStack

Can communicate with:
Cinder - volume store
Glance - gets the img
Quantum
Ceilometer
Keystone -AAA authentication
Neutron

CRUD: - covers the entire life cycle of a system
Create
Retrieve
Update
Delete

REST based JSON or XML
HTTP over TCP
GET - Retrieve
POST - Create
PUT - Update
DELETE - Delete

----
GLANCE: Virtual machine image registration and storage

Very simple, uses:
NOVA
SWIFT - offers an object store, could store the image
CEILOMETER - aggregates all the metered image type, size
KEYSTONE - AAA auth.

basically just a catalog of images

----
Object Storage -
SWIFT: Store and retrieve data

----
IDENTITY
KEYSTONE
Tokens are generated on request to be used to auth each user within openstack and each component

----
DASHBOARD
self service - HORIZON

MVC approach

Contoler is the business logic

view is how the logic is presented to the user

model is the engine of the code

----
NEUTRON - netowrking component

----
CINDER - volume store
gives you a block of storage ( external )

external long lasting psychical drives separate from the VM to be attached
Multiple vlumes to one VM but not multi VM to one volume

----
CEILOMETER
Billing for the VM
cycles
men used
bytes in bytes out

----
HEAT
Desgin for applications
in a txt file:
what makes up a cloud app
how they are linked up in a VM
what order the VMs have to be started

----
SAVANNA
offers Hadoop - allows parallel processing for processing data
     used a lot for data mining

----
## Basic Servers
----
os390 first successful model
as400 server was more successful

different types of servers:

* files - shares files

* printers - lets users print the file you are sending to print is about 10x the size of the original file

* web

* application
