Various Portfiles for installation of Orocos on OS X.

Using This Repository
=====================
The following steps will allow you to use the portfiles in this repository with your local macports installation. Please replace /Users/vm with your local home directory as appropriate.

1. Clone the repository locally:

	$ cd ~

	$ git clone https://github.com/smits/smits-macports.git

2. Edit /opt/local/etc/macports/sources.conf to include the path to the local clone:

	file:///Users/vm/smits-macports

	Be sure that this line is above the rsync:// line.

3. At this point, you should be good to install the included ports, such as lua51:

	$ sudo port install lua51

