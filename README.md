SSHFS Mount Helper
=================

This is a bash function that allows you to mount SSHFS share faster.

This is to be sourced from .bashrc or .bash_profile. Then you can use mnt to
quick mount sshfs volumes.

Examples
--------

	$ mnt
mount the default volume skywalker: on /Volumes/skywalker

	$ mnt host
mount sshfs://host on /Volumes/host
	
	$ mnt host:
same as above

	$ mnt host:/root
mount sshfs://host/root on /Volumes/root

	$ mnt host/root
same as above

	$ mnt host.example.com:/home/hippi
mount sshfs://host.example.com/home/hippi on /Volumes/hippi

	$ mnt host.example.com
mount sshfs://host.example.com on /Volumes/host

	$ mnt edc@remote.host.com
mount sshfs://edc@remote.host.com on /Volumes/remote


