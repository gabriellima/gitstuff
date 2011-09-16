++++++++++++++++++++++++++++++++++++++++++++++++
Gitstuff - This likely will save your time
++++++++++++++++++++++++++++++++++++++++++++++++

Needs (If any of your answers are yes, than this project is for you!)
=====================================================================

1) Do you have a work folder with many subfolders managed by git, each one with many remote branches?

.. highlight:: shell

::

    git up-dirs


Installing
===========

.. highlight:: shell

::

    git clone git://github.com/gabriellima/gitstuff.git
    cd gitstuff
    sudo cp ./scripts/* /usr/local/bin/

Using
=======

**git up-dirs**
----------------

Suppose I have a folder called 'workspace', that looks like this:

.. highlight:: shell

::

    $ ls ./workspace
    project-1         project2         project-3

Each of this sub-folders (project-1..3) are managed by git, and also have many remote branches.

How could I automate the process of going into each folder and then ``git pull`` each branch of the subfolders?

.. highlight:: shell

::

    $ cd ./workspace
    $ git up-dirs

Hooray! All branches in all subfolders were pulled! Just like this.


Contribute
===========

* Source hosted at `GitHub <http://github.com/gabriellima/gitstuff>`_
* Report issues on `GitHub Issues <http://github.com/gabriellima/gitstuff/issues>`_

Pull requests are very welcome!

