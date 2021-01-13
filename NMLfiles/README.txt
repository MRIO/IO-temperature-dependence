The folder NMLfiles contains all NML files that are needed to run the jupyter notebooks. 

Inside NMLfiles there are five subfolders: 
- Cells contains all available cell NML files. These cell NML files include channel NML files. For some, these have to be located in the same folder as the cell NML file itself, hence you find all channel NML files in the folder Cells as well. For some other cell NML files, the channel NML files have to be inside a folder called channels at the same level as the Cells folder. Therefore, the same channel NML files are located in this folder as well. Make sure you always have a copy of the same channels in this folder. 
- channels is the folder I just refered to.
- channels_noQ10 contains a copy of all the "original" channel NML files I started with. I ran no simulations with them.
- channels_Q10of3 contains all the needed channel NML files with all Q10 parameters set to have value 3. 
- channels_variableQ10s contains all needed channel NML files but with Q10 parameters based on literature. References can be found in overview_conductances.xlsx. 
To run simulations with either of the channel NML files (say, f.e., Q10 variable), copy the contents of the channel_variableQ10s to both the Cells and Cells\channels folder (and overwrite the channel NML files already present there) and you are ready to go. 