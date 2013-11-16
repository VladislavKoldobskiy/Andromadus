CyanogenMod
===========

Getting Started
---------------

To get started with Android/CyanogenMod, you'll need to get
familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

To initialize your local repository using the CyanogenMod trees, use a command like this:

    repo init -u git://github.com/CyanogenMod/android.git -b cm-10.2

Then to sync up:

    repo sync

Please see the [CyanogenMod Wiki](http://wiki.cyanogenmod.org/) for building instructions.

You'll also need to add [local manifests](http://wiki.cyanogenmod.org/w/Doc:_Using_local_manifests) from this repository to your .repo/local_manifests.
