froyocomb: Honeycomb Restoration Project 
===========

This repository contains manifests for AOSP tool `repo`, that download source code of Android 3.0 ("Honeycomb") builds (including pre-release and final releases, which are hardly available in form of source code). 

Following builds were reconstructed:

| Build number                             | Status           |
| :---:                                    |   :---:          |
| [`HRG15`][HRG15] (July 15, 2010)         | Work in progress |
| [`HRG30`][HRG30] (July 30, 2010)         | Done             |
| [`HRG44B`][HRG44B] (August 13, 2010)     | Done             |
| [`HRG61`][HRG61] (August 30, 2010)       | Done             |
| [`HRG85C`][HRG85C] (September 27th, 2010)| Done             |
| [`HRH27`][HRH27] (October 27th, 2010)    | Done             |
| [`HRH54C`][HRH54C] (November 24th, 2010) | Done             |
| [`HRH83D`][HRH83D] (December 27th, 2010) | Done             |
| [`HRI39`][HRI39] (Android 3.0 r1)        | Work in progress |

[HRG15]:  https://github.com/Typicals-Android-Stuff/froyocomb/tree/HRG15
[HRG30]:  https://github.com/Typicals-Android-Stuff/froyocomb/tree/HRG30
[HRG44B]: https://github.com/Typicals-Android-Stuff/froyocomb/tree/HRG44B
[HRG61]:  https://github.com/Typicals-Android-Stuff/froyocomb/tree/HRG61
[HRG85C]: https://github.com/Typicals-Android-Stuff/froyocomb/tree/HRG85C
[HRH27]:  https://github.com/Typicals-Android-Stuff/froyocomb/tree/HRH27
[HRH54C]: https://github.com/Typicals-Android-Stuff/froyocomb/tree/HRH54C
[HRH83D]: https://github.com/Typicals-Android-Stuff/froyocomb/tree/HRH83D
[HRI39]:  https://github.com/Typicals-Android-Stuff/froyocomb/tree/android-3.0_r1

Downloading Source
------------------

To get started with downloading the source code, you'll need to get familiar with Git and [`repo`](https://source.android.com/docs/setup/reference/repo).

To initialize a repository tree using one of the manifests provided by this project, execute a command like this (see the table above for available branches):

    repo init -u https://github.com/Typicals-Android-Stuff/froyocomb.git <branch>

Then to download the respective code, execute:

    repo sync

Compiling
---------

For installing dependencies, refer to the article ["Initializing a Build Environment"](https://web.archive.org/web/20140208084633/http://source.android.com/source/initializing.html) from the AOSP documentation.

To initialize the build environment, execute the following command:

    source build/envsetup.sh

Then pick from one of the available build targets by executing the command:

    lunch

	
	
