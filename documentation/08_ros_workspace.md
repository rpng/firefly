# Setting up ROS Workspaces

This will go over the best practices when setting up a ROS workspace.

A typical workspace is a directory as such:

* /home/asctec/workspace.

Catkin build will attempt to build all of the packages that are in a workspace so for working on several different projects it is advisable to have the workspace set up as such:

* /home/asctec/workspaces/catkin\_ws_*projectname*

These workspaces are created by using the normal mkdir command.

Once the workspace has been created you need to create subdirectory called src in the workspace. This will contain all of your source code for your packages.

Next is to create a package in the src directory. This is done with the `catkin_create_pkg package-name` command. Note that ROS packages follow a naming convention that only allows lowercase letters, numbers, and underscores and requires that the first character to be a letter. 

A final example of a working workspace is as follows:

* /home/asctec/workspaces/catkin\_ws_visensor