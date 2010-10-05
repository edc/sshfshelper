SSHFS Mount Helper
=================

This is a bash function that allows you to mount SSHFS share faster.

This is to be sourced from .bashrc or .bash_profile. Then you can use mnt to
quick mount sshfs volumes.

Examples
--------

	$ mnt
this would mount the default volume skywalker: on /Volumes/skywalker

	$ mnt host
this would mount sshfs://host on /Volumes/host

	$ mnt host/root
this would mount sshfs://host/root on /Volumes/root

	$ mnt host.example.com/home/hippi
this would mount sshfs://host.example.com/home/hippi on /Volumes/hippi

	$ mnt host.example.com
this would mount sshfs://host.example.com on /Volumes/host


