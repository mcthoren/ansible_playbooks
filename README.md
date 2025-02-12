This is a collection of the playbooks I use and have used for playing around with a fleet of Raspberry Pis.


When a Pi is first booted the following playbook should pull in everything I need to get it running.
* rpi_initial_setup.yml

I used to run things like Ganglia and NFS, I don't anymore but I've left the playbooks in case anyone finds them useful. There are also playbooks for upgrading major versions of debian/raspios/raspbian that typically only get used once of course. A few playbooks are there for things like migrations from nfs to ssh or between file servers.
