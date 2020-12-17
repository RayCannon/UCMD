# UCMD
Pseudo User Commands for Dyalog APL under Windows

These pseudo user commands were developed before Dyalog added their own []UCMD commands.

Unlike Dyalogs UCMDs which use the "]command" form they are actiond on a keybord via []SE.UCMD.
However, I normally action them using a mouse on buttons added to the Dyalog menu bar.

All the pseudo commands are stored in a single directory which is used exclusivly for this purpose.
Each command is stored in a Dyalog workspace under this directory. (last saved under Dyalog 17.0)
You should copy this directory from here onto your PC.
Then within Dyalog load the file start.dws. 
On the inital load it will set up your  Dyalog Session (PFKeys and Menu items etc) and workspace path.
This information is stored in your Registry for future use.

I suggest you DO NOT save the modified session, as it will be recalled from the Registry each time "start.dws" is loaded.
If you wish to save other changes to your session, first select the option "Reset session - Remove Pseudo User Commands"
which has been added to the standard "Session" drop down menu via "start.dws".

