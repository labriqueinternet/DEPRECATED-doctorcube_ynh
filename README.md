# Doctor Cube

YunoHost application to push things related to the Internet Cube to our
members.

RIGHT NOW THIS IS A BETA AND WILL BREAK THE WORLD IF YOU TRY TO USE IT.

**We need testers for this app**.

It contains the script to fix the 4.5 kernel bug.

To install (remember what I've said about breaking the world?):

    yunohost app install https://github.com/labriqueinternet/doctorcube_ynh --verbose

Things that this app do:

* fix the 4.5 kernel bug (by not installing it and moving back to debian stable for the linux kernels)
* app labriqueinternet.json app list
