Vagrant
=======

This repo is a place for me to keep track of what I'm doing with [vagrant](http://vagrantup.com).  It incorporates a lot of others' work.  It is [Puppet](http://puppetlabs.com) centric.

Do take the time to familiarize yourself with the awesome work the people behind these projects are doing and contribute if you can, even if it's only to spread the good word.

# VMs
I built these VMs using [Packer](http://packer.io).  Each VM is more fully described in other github repos:
* [CentOS](https://github.com/bkyoung/packer-centos.git)
* [Ubuntu](https://github.com/bkyoung/packer-ubuntu.git)

There are several modules I pulled from Puppetforge a long while ago (that need updating, now).  I was playing with Jenkins.  The important thing about these projects is the Vagrantfile examples they provide.
# Modules Used
* [puppetlabs/stdlib](http://forge.puppetlabs.com/puppetlabs/stdlib)
* [puppetlabs/firewall](http://forge.puppetlabs.com/puppetlabs/firewall)
* [7terminals/java](http://forge.puppetlabs.com/7terminals/java)
* [rtyler/jenkins](http://forge.puppetlabs.com/rtyler/jenkins)

# Notes
* You will need to download the [Oracle JDK6](http://download.oracle.com/otn-pub/java/jdk/6u45-b06/jdk-6u45-linux-x64.bin) into modules/java/files/
