# GistList

This repo will be for providing easy access to some of the gists i post. From time to time i'll write a script for a specific 
purpose, for personal use, or to help out a friend with something. As opposed to most of my Open Source projects these scripts tend to be more practical in nature meaning that they are usually a little less user friendly and just simply get the job done.

However, since a number of these scripts might be useful to others for various reasons, i decided it might be helpful to post a neat list of them here with a short description on their functionality.

Check the list out below, i will be periodically updating it as we move forward.

### Geo Sorter

A small wrapper, for [Stamparm's](https://github.com/stamparm)  [Fetch-Some-Proxies](https://github.com/stamparm/fetch-some-proxies) that allows you to easily gather some secure proxies sorted on pre-configured geo-locations.

Find it [here](https://gist.github.com/NullArray/35e3d894fe896ee1d7d8088a3d8175b7).


### GenCert

This little shell script will quickly go over the steps needed to setup an OpenSSL cert.

Find it [here](https://gist.github.com/NullArray/de1406d4e18790a861574f7cffdbc3d4)

### Config Script To Run Android in VM with QEMU

I recently switched from VMware to QEMU for OS virtualization. During that time i wanted to run Android in VM, this Bash script will help you set up an IMG file to emulate Android's internal storage. After that the script will use an ISO of Android and the IMG file to start an Android VM with QEMU. 

Find it [here](https://gist.github.com/NullArray/1384c4aae7e73eeb51b620b1abcf6ea7)

### Optional Libraries Installer (QEMU/Ubuntu)

This is a small shell script that installs optional supporting libraries for QEMU-KVM. Written for use on Ubuntu.

Find it [here](https://gist.github.com/NullArray/c0ff340cd70ad159a60939bc6e4c0f9e)

### Copy-Locker

This Bash script was written for the purpose of finding all files and directories that have been modified in the last hour. And Zip them up in a password protected archive. Uncomment line 43 and comment line 44 in order to force the script to look for log files instead and perform the same operation on those.

Find it [here](https://gist.github.com/NullArray/a4bb0c513df0bf826268cfe154d985ed)


### Crunch-Wrap

I wrote a little wrapper for the `crunch` utility for a friend of mine. The main feature is that this Python script uses regex to filter out results that only consist of a string of numbers.

Find it [here](https://gist.github.com/NullArray/c5d127ec48aea708525936e762904312)



As i write more snippets or small programs/scripts of a similar nature i will be updating this page. If you have any questions regarding anything i posted here feel free to [Open a Ticket](https://github.com/NullArray/GistList/issues)

Thanks.
