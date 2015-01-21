title: Connecting Tableau to Hadoop Hive using a Cloudera Quick Start VM Hosted
In Hyper-v
date: 2015-01-15 09:52:36
tags:
- Tableau
- Hadoop
- Cloudera
- Hyper-v
---

I was recently tasked for a project that required connecting Tableau Desktop to
a Hadoop / Hive data source. Since I've only heard of Hadoop at the water cooler,
I had to put my Google skills to work.  I found that Cloudera offers several excellent
quick start virtual machines that I could use.

Vms can be found here : [Cloudera VMs](http://www.cloudera.com/content/cloudera/en/downloads/quickstart_vms/cdh-5-3-x.html)

And they currently have VMs for
- VMWare
- Virtual Box
- KVM

I however, needed a Hyper-v version since that is the hosting technology of choice for this project.

After some research and trial and errors, I found Starwind's V2V converter [download site](http://www.starwindsoftware.com/v2v-converter-download) So I downloaded both the converter and a copy of Cloudera's VMWare VM quickstart [download](https://downloads.cloudera.com/demo_vm/vmware/cloudera-quickstart-vm-5.3.0-0-vmware.7z)

#### Hyper-v Setup Steps
1. Install Starwind's V2V converter [download site](http://www.starwindsoftware.com/v2v-converter-download)
2. Download and decompress the VMWare vm [download](https://downloads.cloudera.com/demo_vm/vmware/cloudera-quickstart-vm-5.3.0-0-vmware.7z)
3. Run the Starwind Converter and browse to the decompressed vmware folder that contains the vmware disks
4. Convert the files to a VHD
5. Within Hyper-V create a new VM and name it whatever you wish. (I named mine Hadoop)
6. The VM requires quite a bit of horsepower so I set mine to use 2
virtual processors and 8 GB of memory.  I did get it working with less power however using 4 GB and 1 processor, but obviously had diminished results.
7. Attach the newly converted hard drive aka vhd to your newly created Hyper-V vm.
8. Power On

### Cloudera Quick Start VM Setup




### Connecting a Tableau Workbook to Hadoop Hive
