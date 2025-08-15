Honeycomb Restoration Project (Froyocomb)
===========

This repository contains reconstructed manifests of Honeycomb builds. As of now, following builds were reconstructed:


| Build number                    | Status           |
| :---:                           |   :---:          |
| `HRG30` (July 30, 2010)         | Work in progress |
| `HRG44B` (August 13, 2010)      | Done             |
| `HRG61` (August 30, 2010)       | Done             |
| `HRG85C` (September 27th, 2010) | Done             |
| `HRH27` (October 27th, 2010)    | Done             |
| `HRH54C` (November 24th, 2010)  | Done             |
| `HRH83D` (December 27th, 2010)  | Done             |
| `HRI39` (Android 3.0 r1)        | Work in progress |

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
	
	
