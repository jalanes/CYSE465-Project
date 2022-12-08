# CYSE 465 final project

Tasks and contributions:

- Become familiar with the platform strucuture of Autoware, its perception stack, user interface, the functions that are available through the runtime manager, as well as what is needed for the system set up by reading the manual found on: https://github.com/CPFL/Autoware Manuals/blob/master/en/Autoware_UsersManual_v1.1.md#installation
- Learn the process of creating a new map in the SVL simulator in case a new one is needed for testing by following these steps: https://www.svlsimulator.com/docs/simulation-content/add-new-map/
- Learn to deploy ADE as it is a docker container that will be needed  to run apollo along with LGSVL simulator to run our attack scenario. The following commands were used: ade start, ade enter, source /opt/ros/dashing/setup.bash, sudo apt update, sudo apt install ros-dashing-turtlesim, sudo apt install ros-dashing-rqt-*, sudo apt-install byobu. These are the commands to update the system and install ros dashing and other tools
- Found and provided documentation on a testing session that goes over how to start multiple ADE instances as well as the commands needed to clear unused docker images as storage was one of our constraints and as we did more testing we accumulated unused images : https://ade-cli.readthedocs.io/en/latest/usage.html
- Become familiar on how to launch apollo alongside the SVL simulator for testing sessions by following the steps found here: https://www.svlsimulator.com/docs/system-under-test/apollo5-0-instructions/
- Attend all the meetings created by the team to discuss the project's progress and direction, 
