eb09_v1

This readme.txt file was generated on 2025-01-20 by Peter Melville Logan. View complete information at  https://tu-plogan.github.io/source/r_9th_edition.html.

GENERAL INFORMATION

    1. Title 
        Encyclopedia Britannica, 9th Edition: A Machine-Readable Text Transcription

    2. Author Information
	    Principal Investigator
            Peter Melville Logan
		    Temple University
		    Philadelphia, PA 19122 USA
		    peter.logan@temple.edu
		
        Associate Investigator
            Jane Greenberg
            Drexel University	
	        Philadelphia, PA 19104 USA
	        jg3243@drexel.edu

        Associate Investigator
		    Don Kretz
		    Distributed Proofreaders 
		    https://www.pgdp.net/c/ 
		    dakretz@gmail.com 

    3. Date of data collection
        2014-2020

    4. Funding sources
        National Endowment for the Humanities HAA-261228-18
        Institute of Museum and Library Services
        Temple University Libraries
        Temple University Presidential Humanities and Arts Award
        Temple University College of Liberal Arts Research Award
        Temple University Office of the Provost


SHARING/ACCESS INFORMATION
    Licensed under a Creative Commons Attribution 4.0 International License. CC BY 4.0. 2024.
    
    Also available at 
        - King's Digital Lab, King's College, London, https://kingsdigitallab.github.io/eb-pre/
        - GitHub at https://github.com/TU-plogan/kp-editions


DATA & FILE OVERVIEW

    1. Directory Structure
     
        eb09            : Root directory for entry files in Encyclopedia Britannica, 9th edition
            TXT_v1      : Directory of plain text entry files, version 1
                a1      : Subdirectories for entries under the given letter and volume number                
                a2   a3   b3   b4   c4   c5   c6   d6   d7   e7   
				e8   f8   f9   g10  g11  h11  h12  i12  i13  j13
				k13  k14  l14  l15  m15  m16  m17  n17  o17  o18
				p18  p19  p20  q20  r20  r21  s21  s22  t23  u23
				u24  v24  w24  x24  y24  z24
            XML_v1      : Directory of TEI-XML entry files, version 3
                a1      : Subdirectories for entries under the given letter and volume number                
                a2   a3   b3   b4   c4   c5   c6   d6   d7   e7   
				e8   f8   f9   g10  g11  h11  h12  i12  i13  j13
				k13  k14  l14  l15  m15  m16  m17  n17  o17  o18
				p18  p19  p20  q20  r20  r21  s21  s22  t23  u23
				u24  v24  w24  x24  y24  z24
			README.txt  : This information file

    2. Filename Convention
        Filenames are designed so that (1) files are alphabetically ordered in their original
        sequence, and (2) the source can be easily located in the print edition. Names contain 
        information specifying edition, volume, page number, and sequence of items on the page 
        for each entry in the encyclopedia. Example: “kp-eb0901-009905-1114-v1.txt” 
            o	kp 		    = Knowledge Project
            o	-eb0901 	= Encyclopedia Britannica, 9th ed., print vol. 1
            o	-009905 	= print page 0099, 5th entry beginning on the page
            o	-1114 		= last 4 digits of the source image filename (insures URI uniqueness)
            o	-v1 		= version 1
            o	.txt 		= plain text (or .xml for TEI)

    3. Other Versions
        Previous versions of the data set are available at 
        https://github.com/TU-plogan/kp-editions/tree/main/eb09


METHODOLOGICAL INFORMATION

    1. This data set was generated using Optical Character Recognition (OCR) on page image files 
    of the encyclopedia. Further information about the sources and methods of OCR is online at 
    https://tu-plogan.github.io/source/c_ocr.html.

    2. The raw data was processed using Python and XSLT to produce individual TEI files for each
    entry in the encyclopedia. An automated system of OCR error-correction was done with Python 
    and PHP. Further information is online at 
    https://tu-plogan.github.io/source/c_processing_entry_files.html.
    
    3. Each TEI entry file has subject keywords for the entry in the <teiHeader>. Keywords 
    were generated using the RAKE algorithm with the HIVE2 vocabulary-server maintained by the 
    Metadata Research Center at Drexel University. Further information is online at 
    https://tu-plogan.github.io/source/c_master_files.html.
    
    4. Contributor names:
		Editor
			Peter Melville Logan, Temple University
		
		Consultants
			Don Kretz, Distributed Proofreading
			Matthew L. Jockers, Apple
			Joseph T. Tennis, University of Washington
			Jane Greenberg, Drexel University
			Marcus Bingenheimer, Temple University
			Julia Flanders, Northeastern University
		
		Research Assistants, Drexel University
			Samantha Grabus
			Sonia Pascua
		
		Research Assistants, Temple University
			Bethany Farrell
			Ian Gates
			Tyler Gittelman
			Mateline Hammell
			Luling Huang
			James Kopaczewski
			Nhan Nguyen
			Katie Rogers
			Rachel Stover
			Joyce Rasing
			Gary Scales
			Andrea Siotto
		
