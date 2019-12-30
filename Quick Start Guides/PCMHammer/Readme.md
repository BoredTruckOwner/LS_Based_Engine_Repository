## Get the latest release @ https://github.com/LegacyNsfw/PcmHacks/releases
## If you have any issues you can contact the developers by creating a new thread @ http://pcmhacking.net
## It is highly reccomended that you initially read and save your bin in a safe place as a failsafe.
# What is PCMHammer?
PCMHammer is a PCM flashing utility, it is not a one stop shop like some of the commercial products out there. 
PCMHammer enables you to retrieve and send data to the PCM, basically email for your PCM. 
That being said, PCMHammer cannot modify the data given to it, for that a tuning utility such as TunerPro is used.
# What is TunerPro?
TunerPro is an Excel spreadsheet on steroids, it interprets the binary file (.bin) using a definition file (.xdf). 
The definintion file is, in extremely basic terms, a big dictionary for where to look for tables and flags. 
There aren't that many XDFs for our PCMs because it requires extensive reverse engineering, imagine writing a dictionary for a language while you learn it.
# How do I get stuff from TunerPro to PCMHammer?
Everyone has a different way of doing it, I recommend you create a folder on your desktop and save all bins/tunes to said folder. From there its as easy as selecting that folder from your desktop and choosing the tune you want.
While not required it is highly reccomended you keep extensive notes on what changes you have made, and iterate versions so that if you make a change that doesnt work you have somethign to revert back to.
It's also good tuning practice to only work on one thing at a time, that way you can easily backtrack to what may be causing an issue should one arise.
# What can I use with PCMHammer?
There is currently a short list of the devices that can be used with PCMHammer, the easiest and quickest way to check is to visit https://github.com/LegacyNsfw/PcmHacks/wiki/SupportedDevices
# Does PCMHammer datalog like the other commercial products?
PCMHammer has a seperate basic datalogger that outputs a CSV file that can be imported into Excel or a similar program.
If you are using one of the supported bluetooth products, you can also download an app such as Torque to datalog in much the same format.
# I have PCMHammer and TunerPro, what do I do now?
Contribute! This repository can only get bigger and who knows, if theres enough demand we might see some more open source friendly software. 
If you want to learn to tune there are many resources online, tuning let alone OEM tuning has a lot of data that can overwhelm you, it helps to wait a bit and read up on what everything does first.
# I'm ready to tune, but I don't know which PCM I have.
If you have your PCM just sitting on the bench just take a look at your hardware ID, if your PCM is tucked away in a some crevice of your car, then you can use PCMHammer's "Read Properties" function to check what PCM you have.
Final option is to search the vehicle/donor VIN on GM's official site @ https://tis2web.service.gm.com/tis2web/
