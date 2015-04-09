MkCloud Runs
------

Run multiple instances of mkcloud in parallel.

Configuration
> Configuration is fairly easy. I have configured mkcloud to use a seperate
> hard disk with LVM volumes setup.

Steps
> Go learn it yourselves, I'm not your baby sitter!

Inspiration
> I'm just too lazy.

This looks kool
> Nah, its just stupid.

No seriously I think I want to try this shit out ...
> Hmm, ok here are the details


##Installation

* Clone the repository
* Create a LVM drive either using dd or give it one partition from your disk
drive.
* Get some coke, and coffee (thats for me)
* Create PV and LV and give the LV name in the config file. For me it is
libvirt.

##Parallel Mkclouds

* To find out the required IP addresses of the mkcloud steup, go through the
  mkcloudrun file in this folder. Usually the formual is good to guess the
required IP addresses.
* Crowbar admin IP is at xxx.10.

##RoadMap

* Add manual hostname entires to /etc/hosts.
* Add cleanup functionality.
* Add offline support.
