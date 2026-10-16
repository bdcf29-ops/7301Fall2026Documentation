# Installing nano and apache2 

To install nano, use the command: sudo apt install nano

To install apache, first search for the packages, using the command: apt search apache2 | head

Out of the options listed, we want regular apache2. To learn more information about the package, its version, if it's a necessary package, where it works, and if it is an Ubuntu package, use the command: apt show apache2

Then we can install apache2 using the command: sudo apt install apache2

To check if apache2 is running correctly, use systemctl with the following command: systemctl status apache2

