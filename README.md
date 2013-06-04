Vagrant
=======

This repo is a place for me to keep track of what I'm doing with [vagrant](http://vagrantup.com).  It incorporates a lot of others' work.  It is [Puppet](http://puppetlabs.com) centric.  I am slowly implementing the ideas described on the Puppet Labs blog for [continuously integrating puppet](https://puppetlabs.com/blog/release-management-blog/video-continuous-integration-for-your-puppet-code/?utm_source=feedburner&utm_medium=feed&utm_campaign=Feed%3A+PuppetLabs+%28Puppet+Labs%29).  I'm learning new things as I go.  It's an adventure.

Do take the time to familiarize yourself with the awesome work the people behind these projects are doing and contribute if you can, even if it's only to spread the good word.

# VMs
I built these VMs using [veewee](https://github.com/jedi4ever/veewee).  Both VMs are completely stock standard VMs generated from the templates, with the following notes:
* Chef and Puppet are not installed.  Instead, I chose to make use of Mitchell Hashimoto's [puppet-bootstrap](git://github.com/hashicorp/puppet-bootstrap) scripts to install puppet at 'up' time using a shell provisioner.

# Modules Used
* [puppetlabs/stdlib](http://forge.puppetlabs.com/puppetlabs/stdlib)
* [puppetlabs/firewall](http://forge.puppetlabs.com/puppetlabs/firewall)
* [7terminals/java](http://forge.puppetlabs.com/7terminals/java)
* [rtyler/jenkins](http://forge.puppetlabs.com/rtyler/jenkins)

# Notes
* You will need to download the [Oracle JDK6](http://download.oracle.com/otn-pub/java/jdk/6u45-b06/jdk-6u45-linux-x64.bin) into modules/java/files/
