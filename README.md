# deployment-script

# Implementing the deployment script

-The main advantage of the scripted solution is the simplicity and ease of configuration of the remote servers. However, 
 such an approach can reach its limits if you need to implement more advanced
 deployment actions, such as installing a software , configuring a service, or simply running any command line on your servers.
 
# Requirements

-Insatalling sshpass : Designed for running ssh using the mode referred to as "keyboard-interactive" password authentication, but in non-interactive mode.

-Creating the csv file that contains the list  of servers that you will command.This file must be saved in a table structured format:
EXMPLE: "@IP:LOGIN:PASSWORD".

-Create the command file that contains the commands that will be executed on the remote servers.
