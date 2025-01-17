# Jenkins and Docker Tutorial Series

This repository is provided as a set of functional working examples that follows along with a blog series released by Maxfield Stewart at Riot Games (http://live-rg-engineering.pantheon.io/news/putting-jenkins-docker-container).  Each folder contains a self contained set of files that are the end result of each tutorial and are provided as is.

# Instructions

Ideally users should follow the blog series for specific directions.  That said here's some basic setup instructions you will need before these become viable.

# Step 0 - Pre-Reqs

1. You’ll need Windows 7 (or later) or Mac OSX 10.7 or later.
2. You’ll need a machine that’s able to run VirtualBox - you may need to enable virtualization in your BIOS on some PC’s.
3. If you already have Docker Toolbox installed, you can skip step 1 below. This blog was written using Docker Toolbox 1.8 and Virtualbox 5.

   Please note: when installing Docker Toolbox on a system with a pre-existing Virtualbox install you may run into some interesting challenges that are best to get around by uninstalling everything and installing from scratch.

   If installing a new version of Docker Toolbox over a very old version of Boot2docker you may run into issues, it’s best to fully wipe Boot2docker and its iso images before proceeding.

# Step 1 - Install Docker Toolbox

1. Go to: http://docks.docker.com/installation/mac  (or http://docks.docker.com/installation/windows)
2. Download and install Docker Toolbox for your operating system. Please keep in mind that behind the scenes this is installing VirtualBox.
3. Follow all setup instructions.
4. Verify your installation is working by opening a docker terminal window (in windows this step is done by clicking the docker quickstart desktop icon) by running the following steps:
5. Type: docker images (verify it gives you an empty list back with no errors).


