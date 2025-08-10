Honeycomb Restoration Project (Froyocomb)
===========

This repository contains reconstructed manifests of early Honeycomb builds. As of now, one build, HRG85C from September 27nd, 2010 was reconstructed.

<img width="70%" height="70%" alt="Screenshot of HRG85C" src="https://github.com/user-attachments/assets/61188d77-6b4e-4051-acbf-fee3fbe692f4" />

Getting Started
---------------

To get started with Android, you'll need to get
familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

To initialize your local repository using the Android trees, use a command like this:

    repo init -u https://github.com/Typicals-Android-Stuff/froyocomb -b HRG85C

Then to sync up:

    repo sync

Compiling
---------

For installing dependencies, refer over to this [site](https://web.archive.org/web/20130128005045/http://source.android.com/source/initializing.html). To initialize build environment, use a command:

    . build/envsetup.sh
	
Then, pick up from available compilation options by using command:

    lunch
	
	
