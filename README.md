ofxVstHost
=====================================

Introduction
------------
Enable to load VST plugins and use them as audio effects in openFrameworks.

(perevalovds fork from Meach/ofxVstHost)

License
-------
See `license.md`.

Installation
------------
1. Go to `https://www.steinberg.net/en/company/developers.html` and download the VST SDK.
(https://archive.org/details/VST2SDK)
1. Extract the VST SDK on your computer and copy the `pluginterfaces` folder inside the addon `lib\VST2_SDK\` folder. 



Free VST
------------
* Example includes MVerb https://rekkerd.org/martin-eastwood-audio-free-plugins/
* List of free VST effects: https://blog.landr.com/best-free-vst-plugins/#bestfreevsteffects
* http://magnus.smartelectronix.com/#Ambience

Dependencies
------------
None.

Compatibility
------------
OF 0.10.1 Win, VST SDK 2.4.


#### Architecture
Make sure the VST architecture (32/64-bit) match your project architecture!


Known issues
------------
VST editor not implemented (i.e. VSTi cannot be displayed).
