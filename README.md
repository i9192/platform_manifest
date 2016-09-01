CAF based AOSP for Samsung S4 mini duos
===========

Getting Started
---------------

To get started with Android, you'll need to get
familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

To initialize your local repository using the CAF AOSP trees, use a command like this:

```repo init -u https://github.com/i9192/platform_manifest.git -b n```

Then to sync up:

```repo sync -f -c --force-sync -j8 --no-tags --no-clone-bundle```
