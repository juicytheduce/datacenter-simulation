**Initial Plan**
create a mock data center through ContainerLabs create a redundant Spine-Leaf Network.
Utilize BGP, VLXAN, EVPN, VTEP, ECMP to simulate data center protocols including an OOB Management Switch.
intergrate automation system to easily deploy new spines and leafs based off of template

**Tasks**
**_Planning_**
- create IP assignments, and vlans
- diagram on draw.io
- sheet on protocols being used
  - watch youtube to see bgp n other protocols

**_Network_**
- create network devices
- configure IP's, VLANs
- Leaf config
- Spine config

**_Automation_**
- look into ansible
- make template of spine and leaf configs


**Testing**
- connect webserver and linux container
- ping from different leafs
