# GistList

This repo will be for providing easy access to some of the gists i post. From time to time i'll write a script for a specific 
purpose, for personal use, or to help out a friend with something. As opposed to most of my Open Source projects these scripts tend to be more practical in nature meaning that they are usually a little less user friendly and just simply get the job done.

However, since a number of these scripts might be useful to others for various reasons, i decided it might be helpful to post a neat list of them here with a short description on their functionality.

Check the list out below, i will be periodically updating it as we move forward.

### New

#### THC-Hydra Wrapper.
Quick Wrapper i wrote for Hydra to bypass the maximum password length and split credential files up accordingly.
Untested, probably buggy. But easy enough to fix and change should you desire to.

Find it [here](https://gist.github.com/NullArray/d6aef3fe33ca142130a3648a0d990ed1)

#### Pipper
I wrote a little Python script that makes restoring Python packages more convenient. Normally when restoring a big package file 
you can create with `pip3 freeze` it stops processing the list when `pip3 install -r backups-pkg.txt` encounters a package that
has been deprecated or is no longer available for some reason or another.

Pipper reads in the text file goes over the packages and simply skips the ones that would normally stop the execution of the restoration operations. 

Find it [here](https://gist.github.com/NullArray/9f4a6b0b2817d8be7aec88cad9ef80a6)


#### OPSEC+ 
Here is a little something to frustrate Micro$oft user data mining efforts. A PAC Script, A PowerShell HTTP Server to serve the PAC Data, a batch file to remove Telemetry related updates and for fun a service in C++ that starts it
all as a sub-process for persistence. Although commands to manually add a scheduled task are provided as well.

Find it [here](https://gist.github.com/NullArray/185dab786e72d59fdf65664f253fc06a)


#### NetSet Related

My OPSEC Tool [NetSet](https://github.com/NullArray/NetSet) has a feature that allows you to easily access online resources that may be hepful with Operational Security. Among which are a [list of DNSCrypt-proxy compatible resolvers](https://gist.github.com/NullArray/e9961cb5574656ecf0d35b09c6567e2c) and a [list of valid MAC Addresses](https://gist.github.com/NullArray/0380871a42b608830357f998df735e71). For convenience sake, i have decided to link to those resources here as well.

#### Geo Sorter

A small wrapper, for [Stamparm's](https://github.com/stamparm)  [Fetch-Some-Proxies](https://github.com/stamparm/fetch-some-proxies) that allows you to easily gather some secure proxies sorted on pre-configured geo-locations.

Find it [here](https://gist.github.com/NullArray/35e3d894fe896ee1d7d8088a3d8175b7).


#### GenCert

This little shell script will quickly go over the steps needed to setup an OpenSSL cert.

Find it [here](https://gist.github.com/NullArray/de1406d4e18790a861574f7cffdbc3d4)

#### Config Script To Run Android in VM with QEMU

I recently switched from VMware to QEMU for OS virtualization. During that time i wanted to run Android in VM, this Bash script will help you set up an IMG file to emulate Android's internal storage. After that the script will use an ISO of Android and the IMG file to start an Android VM with QEMU. 

Find it [here](https://gist.github.com/NullArray/1384c4aae7e73eeb51b620b1abcf6ea7)

#### Optional Libraries Installer (QEMU/Ubuntu)

This is a small shell script that installs optional supporting libraries for QEMU-KVM. Written for use on Ubuntu.

Find it [here](https://gist.github.com/NullArray/c0ff340cd70ad159a60939bc6e4c0f9e)

#### Copy-Locker

This Bash script was written for the purpose of finding all files and directories that have been modified in the last hour. And Zip them up in a password protected archive. Uncomment line 43 and comment line 44 in order to force the script to look for log files instead and perform the same operation on those.

Find it [here](https://gist.github.com/NullArray/a4bb0c513df0bf826268cfe154d985ed)


### Crunch-Wrap

I wrote a little wrapper for the `crunch` utility for a friend of mine. The main feature is that this Python script uses regex to filter out results that only consist of a string of numbers.

Find it [here](https://gist.github.com/NullArray/c5d127ec48aea708525936e762904312)



As i write more snippets or small programs/scripts of a similar nature i will be updating this page. If you have any questions regarding anything i posted here feel free to [Open a Ticket](https://github.com/NullArray/GistList/issues)

Thanks.
