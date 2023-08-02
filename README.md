Electronics Boards
==================

This is the `electronics-boards` repository, containing all the electronic boards developed for study and DIY purposes.

Each board has an own folder where there are schematic, layout, firmware, simulations, documents, photos, configuration files, etc.

The board folders follow these rules:
- foldername **name of the board** 
- admitted subfolders:
   - **docs** folder contains documents
      - **datasheet** folder contains useful datasheet
      - **manuals** folder contains reference manual
   - **output** folder contains files for the production of the PCB and board (Gerber files, BOM, PCB Notes, etc.)
   - **kicad** folder contains the KiCad project
   - **pics** folder contains useful photos and videos of pcb, board, setup
   - **sw** folder contains the firmware useful for the board (test, normal operation, etc)
   
Note: folders and files must be named in lowercase

## Git LFS remark
This repository exploits the Git Large File Support ([LFS][1]) to handle the binary files.
To download the binary files, follow the GitHub [instructions][2]. To configure Git LFS, follow these [instructions][3].


[1]: https://git-lfs.github.com/
[2]: https://help.github.com/articles/installing-git-large-file-storage/
[3]: https://help.github.com/en/github/managing-large-files/configuring-git-large-file-storage
