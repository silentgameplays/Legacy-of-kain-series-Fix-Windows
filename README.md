# Legacy-of-kain-series-Fix-Windows
Legacy of Kain Fix for Windows
1. Drop the d3d8.dll file into each Legacy of Kain series game directory on Steam or GoG.
2. For Legacy of Kain: Soul Reaver download and use this good old fix:
* https://ann.nl.tab.digital/s/eqTyj8oSF7fi73b
3. Enjoy
# If you experience crashes at some points,that means the game requires CPU core affinity to be set via Task Manager  for every session:
1. Open Windows Task Manager.
2. Find process for the application by Right-click on its task and press Go to process/details.
3. Right-click on the process and select Set affinity.
4. Deselect all other CPU cores than the ones the process should be allowed to run on. If you want to prevent the process from using Intel's Hyper-Threading (HT) or AMD's Simultaneous Multi-Threading (SMT) CPU cores then deselect all odd CPU cores (so 1, 3, 5, 7, etc).
5. Click OK to apply the change. It will take effect immediately.
6. Repeat each time you launch the game to avoid crashes
# silentgamepls
