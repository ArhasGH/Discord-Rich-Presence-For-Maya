# Autodesk Maya Rich Presence

This plugin will update your status on Discord depending on your scene and project.

## Instructions

Simply move the RichPresence.mll to your C:/Users/Name/Documents/maya/Version/plug-ins and enable it in your Plugin Manager.

A menu will be added to your menubar at the top called Rich Presence, in here you can change the settings according to your needs. Note that turning it off and on too many times in a row can lead to it crashing, if that happens, restart maya and everything will work as usual. Also keep in mind that enabling and disabling it can take a while, but that limitation is set by Discord, there's nothing I can do to change that. Your settings will be saved even if maya crashes and the same settings will apply across multiple Maya versions.
If you run into issues you can disable the plug-in in the Plugin Manager, doing so will reset everything tho make sure to wait until your status has been updated on Discord before enabling the plug-in again otherwise your maya might crash.

I would generally speaking save your files before changing anything, the plugin appears to be stable aside from disabling and enabling the whole plugin too quickly, but testing the long-term stability is not really possible for a single person so make sure to report any issues you run into.