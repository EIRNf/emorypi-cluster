# emorypi-cluster
Emory Raspberry Pi Cluster Project

## For Developers

After cloning
```
git checkout develop
```

Don't ever try to work on `master`. You can't push to it anyways. If you started working on `master` by error, rebase your working branch onto `develop`.

Every time you want to start working on some feature
```
git checkout develop
git branch new-feature
git checkout new-feature
git push -u new-feature
```
Obviously, rename `new-feature` to the issue name/# you are working on.

When you're done writing your feature
1. Rebase your branch on develop
2. Push your branch one last time
3. Initiate a pull request from `new-feature` to `develop` (*NOT* to `master`!)
4. Add at least *one* reviewer.



#NOTES

Motivation: Educational. For students to have access to a low cost/risk distributed system. This allows students to get hands-on experience with Docker and Kubernetes



Challenges
Storage fault tolerance

Assembly
Simon: I have a huge box of motherboard standoff pins of many different sizes

Network File Storage
>= NFSv4

Schedule to work
Request access? Maybe
4pm - 6pm Tues.
Design
Technical
Raspbian
Appearance
Stack

	
https://bitbucket.org/jkiepert/rpicluster/src/master/ 
https://kubecloud.io/setting-up-a-kubernetes-1-11-raspberry-pi-cluster-using-kubeadm-952bbda329c8 

	Endpoint? API?
	HTTP server
routines?


End:
Website/Portal
Fault Tolerance
Steps and Schedule
Workshop/Presentation



Demonstration stuff
Fault Tolerant System
SQL TODO
Monte Carlo Simulations
Matrix decomposition
Byzantine general problem


Links to look at:
Kubernetes Stuff
https://github.com/ramitsurana/awesome-kubernetes
32pi BeoWulf cluster 
http://coen.boisestate.edu/ece/files/20 ... ter_v2.pdf
MPIbased pi cluster 
http://www.southampton.ac.uk/~sjc/raspb ... ampton.htm
WebServer
http://pi.interworx.com
24-node Pi cluster running WSO2 middleware to allow for higher-performance app services operations
http://www.raspberrypi.org/phpBB3/viewt ... 24&t=41449
webserver
http://raspberrywebserver.com/raspberrypicluster/raspberry-pi-cluster.html
Apache Hadoop
http://hadoop.apache.org/
BigData?
https://github.com/PocketCluster/pocketcluster
Beowulf Cluster!
https://www.beowulf.org/overview/faq.html

Architecture

	Master Node
	HTTP Server - Apache, Nginx ← 
	Prototype with Flask

	Frontend - Angular UI, status info - Kubernetes has this
React
Status Info
	
	Slave Nodes



username:
pi
password:
Emory1!

Raspberry Pi Mac addresses
PI 1
b8:27:eb:a0:4b:2b
PI 2
b8:27:eb:88:4f:07

PI 3
b8:27:eb:b8:67:f8

PI 4
b8:27:eb:35:36:5a

PI 5
b8:27:eb:89:00:15
