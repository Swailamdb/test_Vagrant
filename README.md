# Test_Vagrant
Testing machine with Vagrantfile. 
First Machine establishid to test Linux Ubuntu 18.04.3 LTS on windows desktop by vagrant and virtualbox tools using "hashicorp/bionic64" box on vagrant cloud.
Synchronized folder on Windows (the host) with /vagrant folder on Ubuntu (the guest). 
The first thing I noticed with the synchronization I recognized that the path I write in Vagrantfile to the host applied when I wrote it with / like when we type any path in Linux and refused to work when I wrote it with \ like when we type any path in windows . 
