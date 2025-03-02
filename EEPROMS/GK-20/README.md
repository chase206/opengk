#Decoding Filenames

Filenames are broken down into individual parts of the file version. Using the first file as an example:

**Filename:** ca663032_G4TCMD5b_KR77025147_5WY1618E_0240550251-HMC04020501144355KR77027602C.bin 

**ca653032** - Calibration version. 650XXX is a 2Mbit file while 653XXX is 4Mbit files.

**G4TCMD5B** - Intended vehicle model, year, IMMO enabled, software version  
	**G** - GK model  
	**4** - 2002 year (3 - 2003, 4 - 2004 etc etc)  
	**T** - Region. T is UNKNOWN. N is North American  
	**C** - BETA 2.0 CVVT (0 is BETA 2.0 non-CVVT)  
	**M** - IMMO Enabled (S - IMMO Disabled)  
	**D** - UNKNOWN  
	**5** - Software version   
	**B** - UNKNOWN  
	
**KR77025147** - Machine code version.

**5WY1618E** - ECM family and hardware version number.  
	**5WY14XXX** - 2Mbit family 2002-2003  
	**5WY16XXX** - 4Mbit family 2003-2008
