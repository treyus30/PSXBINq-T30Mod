# Treyus30 Mod (T30 Mod)
I was not happy with the way the original PSXBINq would batch process. It has more flexibility the way it is, but is only conducive to a few images at once. 
This mod does not take any commands - it just runs a batch with preconfigured paramters. 

How to use:
1. After downloading PSX images via NoPayStation you will have the default directories: "\pspemu\PSP\GAME\<game folders>\" DOCUMENT.DAT, EBOOT.PBP, and KEYS.BIN
2. Copy the release .zip and extract to "\pspemu\"
3. Rename "\PSP\" with PBP files in it to "\PSX\", or move them over to the one included with the .zip file. 
4. Run "PSXBINq_T30mod.bat" and let it work. No files should be removed other than what the program itself creates. 

Result will be an additional "CDROM" folder in each game folder containing the .BIN and .CUE for each. Further modification of the run_T30Mod.bat file may be done to rename the files to their Game ID based on source folder names in batch series. 

5. (Optional) Use a file manager to delete all .DAT, .PBP, and .BIN files from the subfolders if you do not want them. I am currently choosing to have 3 copies: the original .pkg, .pbp/.dat/key.bin, and resultant .cue/.bin.  

![image](https://github.com/treyus30/PSXBINq-T30Mod/assets/136277393/9f041257-f1ae-4d98-b47d-a8e870c04639)



# PSXBINq
Tool to unpack PSX PBP and convert to .BIN &amp; .cue files Ready for Playstation Classic 
 
 

So what the hell is PSXBINq anyways? And why does this exist? After hours of searching for the right PBP unpacker that gives me the correct .Bin & .Cue files to work on the Playstation Classic, I ended up finding this tiny little exe application called "PSXtract.exe" and you would open up CMD and run some codes to generate some results that Give you the .Bin & .Cue files I so desperately needed to load my USB Thumb drive full of AWESOME Playstation Classics! That little exe did the trick but it wasn't good enough I need more, I needed BETTER. So I started playing around with command lines and finally ended up a totally over the top advanced system of Batch files that automatically takes any EBOOT.PBP file and unpacks and converts them to BIN/CUE files then renames and sends to the "transfer" folder ready to be copied to your USB drive.

Step One. run "PSXBINq.exe" located in root folder. You would be promted to add Games to the "psx" folder that was just created and popped up in a new window. 
after adding the Games/EBOOT.PBP files Click to continue.
From within the PSXBINq application you will have three options to choose from.
 
1) Unpack EBOOT.PBP
2) Delete EBOOT.PBP
3) Exit

Choose Option 1 to Unpack and transfer ALL the PSX EBOOT.PBP files from psx folder.
 
Choose Option 2 to Delete untouched EBOOT.PBP from the downloaded GAME directory. Do you want to Delete the Eboot.PBP? If you Press Y for Yes, this will delete EBOOT.PBP. If you Press N for No, This will keep the untouched EBOOT.PBP.
 
**PSX PBP files are located in "\psx\TITLEID\EBOOT.PBP"

Choose Option 3 to Exit PSXBINq.
After Exiting you may copy over the "transfer" folder that contains the Games .BIN & .Cue files to you're USB Thumb drive for Playstation Classic. Works with latest Project Eris or AutoBleem.
 
Hope you find this little tool helpful and feedback is welcomed.
Enjoy,
Mizzy
