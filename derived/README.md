# Vulgate Glaire - derived folders
* David Haslam (text/module developer) - 19 January 2021
## USFM
This folder contains 73 **USFM** files converted from TEI XML.
* These were systematically renamed using a simple *ad hoc* Windows CMD file.
## OSIS
This folder contains two **OSIS** XML files:
1. The first was made from the USFM using adyeths/u2o Python script.
2. The second was made from the first by adding OSIS markup for variants to the words in verse text that were parenthesised in the original to provide an alternative translation. Further details are listed in **frevulgglaire.conf** which is found under the SWORD folder.
## SWORD
This folder contains **SWORD** module **FreVulgGlaire**
* This was made from the OSIS input file using the **osis2mod** tool from the [CrossWire Bible Society](https://crosswire.org/).
* It was initially created in October 2017 for testing by the developer.
## processing
This folder contains folders used in analysis and conversion
### Analysis
This folder contains various text files extracted from the original, intermediate or derived files.
### Excel
This folder contains some Excel® workbooks that I found helpful while working on this project.
### Tools
This folder contains my **TextPipe** filters and other tools used during text development.
* These are provided "as is" without any commitment to keeping them maintained.
* TextPipe software can be obtained from [DataMystic](https://www.datamystic.com/).
* I have a purchased license to use **TextPipe Standard** and I've been using **TextPipe** since 2001.
#### Notes
1. I have resaved the TextPipe filters in the new *human readable* **JSON** text file format.
2. Input and output paths for these TextPipe filters were not updated when I copied these into the GitHub project.
3. The Windows **subst** command is used *ad hoc* to create virtual drive letters on my PC as and when the need arises. It's a neat way to shorten long file paths.
4. As indicated in the *module*.conf file, the text development was not quite completed in October 2017. There are still a few tasks **TBD**. 
5. Paths to external replace lists may need to be tweaked for some of the TextPipe filters.

