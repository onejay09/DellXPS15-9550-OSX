Depending on your memmap, you need to use OsxAptioFixDrv, OsxAptioFix2Drv or OsxAptioFix3Drv.  

Version 3 is the most advanced with nvram support, but can result in strange behaviour when your memmap is too fragmented (like only displaying „does printf work??“).  

Most time OsxAptioFixDrv(Version 1) is working with slide=0 or without any slide parameter at all. OsxAptioFix2 and 3 require a correctly calculated slide parameter. See https://github.com/wmchris/DellXPS15-9550-OSX/blob/10.13/Additional/slide_calc.md
  
Use AllocFix.efi in combination with OsxAptioFixDrv if you can’t get V1, V2 or V3 to run with correct slide parameters. Use AllocFix only as your last resort!
