succinct_setup_documentation
============================

Ongoing documentation of the set up of succinct

Setting up a Succinct Data Build Environment for Developers
=============================

Batphone and succinct setup (For OSX):
=============================
Requirements:

-GitHub Account – www.github.com

-https://github.com/servalproject/batphone/blob/development/INSTALL.md states 80 MB free space, this is only relevant to batphone, with the android SDK and NDK etc… its more around 10 GB.

-Mac OSX 10.9 working, others not tested. (10.7 supported according to INSTALL.MD)
Supposedly works on Linux, I did not test this.

-Android phone, for testing properly. (IPhone available soon, supposedly)

Recommendations:

Listen to guide, use home directory; I did not, headaches occurred.

Steps:

Clone the batphone(https://github.com/servalproject/batphone/) directory down. Can fork to upload changes to your own GitHub account to avoid having to have master accepting all the time. So:
````
git clone https://github.com/servalproject/batphone.git
````
^^ For clone from master, if forked URL will be the path of batphone in your account.

Once clone is complete the following commands:
````
$ cd batphone

$ git submodule init

$ git submodule update
````

Obtaining version number:
Change change to appropriate directory 'pathway/batphone'
````
$ git checkout master
$ git submodule update

````

Tools required (download):

JDK 1.6 - Obtained from promts (updates or Application telling you to download it + link or http://www.oracle.com/technetwork/java/javase/downloads/index.html

Apache ANT - http://ant.apache.org/bindownload.cgi

Panadoc - https://github.com/jgm/pandoc/releases

SDK- https://developer.android.com/sdk/index.html

NDK- http://developer.android.com/tools/sdk/ndk/index.html

SDK platform package- Done from eclipse:
  
  for those who dont know: From the application eclipse, go to the drop down menu 'Window' and open 'Android SDK          Manager'
 
