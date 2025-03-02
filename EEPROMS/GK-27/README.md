#Decoding Filenames

Filenames are broken down into individual parts of the file version. Using the first file as an example:

**Filename:** ca652040_G2E7TM0B_6577715107_5WY1503B.bin

**ca652040** - Calibration version. 652XXX is a 2Mbit file while 654XXX and 655XXX are 4Mbit files.

**G2E7TM0B** - Intended vehicle model, year, IMMO enabled, software version  
	**G** - GK model  
	**2** - 2002 year (3 - 2003, 4 - 2004 etc etc)  
	**E** - European (N - North American)  
	**7** - Delta 2.7L  
	**T** - UNKNOWN  
	**M** - IMMO Enabled (S - IMMO Disabled)  
	**0** - Software version 1 (5 - Software version 2, updated by Hyundai dealership typically)  
	**B** - UNKNOWN  
	
**6577715107** - Machine code version.

**5WY1503B** - ECM family and hardware version number.  
	**5WY15XXX** - 2Mbit family 2002-2003  
	**5WY17XXX** - 4Mbit family 2003-2004  
	**5WY18XXX** - 4Mbit family 2005-2006  
	**5WY1FXXX** - 4Mbit family 2007-2009  
