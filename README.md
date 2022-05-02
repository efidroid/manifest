EFIDroid
===========

Getting Started
---------------

To get started with EFIDroid, you'll need to get
familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

To initialize your local repository using the EFIDroid trees, use a command like this:

    repo init -u https://github.com/efidroid/manifest.git -b master

Then to sync up:

    repo sync

Please see the [EFIDroid Wiki](https://github.com/efidroid/projectmanagement/wiki/%5BEFIDroid%5D-Build-system) for building instructions.



enabling optional manifest
--------------------------

This can be useful if you want to work on additional EFIDroid projects.

    mkdir -p .repo/local_manifests
    ln -s ../manifests/optional.xml .repo/local_manifests/optional.xml
