To import your new BOARD into Altium:

1. Start the Altium program.
2. From the menu select "File" and then select "Open".
3. Select the file named in the path above ending with ".PcbDoc"
   and "Open" the file.
4. Your board should be viewable within Altium now.

**Warning** Planes will need to be repoured to update the Copper Pour Polygons
1. Once your board is loaded, select the Tools menu from the top Menu Bar
2. Scroll to the Polygon Pours item on the Tools Menu.
3. The Polygon Pours item should expand to show more options
4. Select Repour All Polygons, this will repour all of the polygons.

For additional information, please visit this site:
http://www.accelerated-designs.com/help/Altium_BrdSch_import.html

To import your new LIBRARY PARTS into Altium follow these steps:

1. After running the Ultra Librarian export for the first time, 
   you will need to copy the following files into an area where 
   they can be accessed for all future translations.  They are script 
   files that Altium will need to be able to find.
 	a. UL_Form.dfm
 	b. UL_Form.pas
 	c. UL_Import.pas
 	d. UL_Import.prjScr
 	
2. The above script file will need to be run from within Altium. 
   This can be done by going to File, Open and selecting the 
   UL_Import.PrjScr file stored above.
   
3. Select the UL_Form.pas file form the new project that has loaded,
   and then select runfrom the drop down menu.  You will need to select
   the form again. Run the form.    

3. When the script is run, it will ask you for the file name of the
   Ultra Librarian file to run.  You should select the latest file
   produced with a date code (for instance 2010-02-17_23-12-34.txt).
  
4. The script will open a new Integraged Library project and import 
   the Ultra Librarian data into it.  When complete a message box 
   will pop up saying that import is done.

For additional information, please visit this site:
http://www.accelerated-designs.com/help/Altium_import.html

For a video tutorial, please visit:
http://youtu.be/pih50yx9HYU