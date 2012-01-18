## About this android email app
This repo is forked from the cyanogenmod gingerbread branch.  There are basically 2 files modified to ignore the local security settings and report back to Exchange ActiveSync that everything is implemented.  You'll still get the warning screen that you need to enable a pin etc but it will go away without forcing you to do it.  Feel free to setup pattern lock or no lock if you so choose!

I have been using this on a motorola sholes for months with no issues.

## What to do?
* Checkout the CyanogenMod repo
* cd /android/system/packages/apps/Email
* git pull https://github.com/dloftus98/android_packages_apps_Email.git

After that you can build the entire update package and deploy it to your phone or if you build just the Email module you'll need to boot into recovery, remove the existing Email app and move in the new one.

## Contributors
* The CyanogenMod Team
* Dan Loftus ([@dloftus](http://twitter.com/dloftus))
