# SwiftER-PyECLib

Quick Start:

  Standard stuff to install::
  
    Python 2.6, 2.7 or 3.x (including development packages), argparse, liberasurecode, gf-complete and Jerasure.


 PyECLib depends on the installation of the liberasurecde library. 


  Install PyECLib::

    $ sudo python setup.py install

  Run test suite included::

    $ ./.unittests

  If all of this works, then you should be good to go.  If not, send us an email!

  If the test suite fails because it cannot find any of the shared libraries,
  then you probably need to add /usr/local/lib to the path searched when loading
  libraries.  The best way to do this (on Linux) is to add '/usr/local/lib' to::

    /etc/ld.so.conf 

  and then run::

    $ ldconfig
    
    
    
more info is in README file.
