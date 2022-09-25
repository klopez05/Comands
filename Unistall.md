# Unistall git

To remove just git package itself from Ubuntu edition execute on terminal:

* $ sudo apt-get remove git

### Unistall git and it's dependent packages

To remove the git package and any other dependant package which are no longer needed from Ubuntu Trusty

* $ sudo apt-get remove --auto-remove git

### Puring git

If you also want to delete configuration and/or data files of git from Ubuntu trusty when this will work:

* $ sudo apt-get purge git

To delete configuration and/or data files of git and it's dependecies from Ubuntu Trusty then execute:

* $ sudo apt-get purge --auto-remove git
