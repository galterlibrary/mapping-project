# LCSH/MeSH Mapping Project


The LCSH/MeSH mapping project was begun at Northwestern University in 1990 and continues up to the present time. The goal of the project is to map corresponding LCSH and MeSH headings and enter the mapping data into 750, 780, and 788 linking entry fields in LCSH and MeSH authority records. We envision a number of possible uses for the mapping data such as:

- In OPACs the linking entry fields can be used to generate see also references between equivalent headings in the two systems.
- The mapping data can be used to assist catalogers in assigning subject headings, when only headings from one of the systems are present in a bibliographic record.
- The mapping data can be used by similar projects that are integrating multiple information languages, which need LCSH/MeSH mapping data for their systems.

The scope of the mapping is limited as follows:

- Only topical headings are mapped. Personal and corporate name headings, and geographic headings are not mapped.
- Main heading/subheading combination headings are not mapped to corresponding main heading/subheading combinations. (e.g., the LCSH heading "Cancer--Treatment" is not mapped to its corresponding MeSH heading "Neoplasms--therapy".) On the other hand, main heading/subheading combinations are mapped to their corresponding MeSH phrase headings. (e.g., the LCSH combination heading "Kidneys--Disease" is mapped to its corresponding phrase heading "Kidney Diseases".)

## Using the data 
The authority records with the mapping data are available for download from this GitHub repository. Because these are working files, new mapping data is being added regularly, with progress noted in the progress.txt file. There are two .txt files of MARC authority records converted to text format for LCSH and MeSH data. They can be easily converted back to MARC by changing the file extension to .mrk (mnemonic text format) and using MarcMaker, available in the MarcEdit utility. Legacy data through 2019 is also [available for download](https://digitalhub.northwestern.edu/collections/8c1d851c-a5e6-4790-a867-fa889e66630e) in MARCXML or MARC binary formatted .zip files from Galter's institutional repository.

All of the records are in the MARC 21 Authority Format. In addition to the 750, 780, and 788 fields with the mapping data, the following local fields will be present in many of the authority records:

- 001 Field: Northwestern library management system record number
- 035 Field: In some records a Northwestern former library management system record number
- 550 Fields: In MeSH records with broader and narrower terms (generated from the MeSH tree numbers)
- 690 Field: In some records a local note

The mapping data is kept current by staff of the Galter Health Sciences Library and other collaborators. They review the annual MeSH additions, changes, and deletions, and the weekly LCSH additions, changes, and deletions, and update the mapping data as needed.

Although the authority records have been reviewed for accuracy, there may still be errors. Also other users of these records may disagree with some of the mapping decisions that have been made. We welcome any questions, corrections, comments and suggestions for improvement.

## Learn more
Project documentation, including scope limitations, instructions for adding mapping fields, and mapping examples, are available on this project's wiki page. 

For a complete description of the project's history, and more details about the authority records, see the article by Tony Olson and Gary Strawn: "Mapping the MeSH and LCSH Systems." Information Technology and Libraries, 16(1) (March 1997) p.5-19.

Please contact [Gretchen Neidhardt](mailto:gretchen.neidhardt@northwestern.edu), Metadata and Digital Projects Librarian, with your queries, or if you would like to be added to the project's listserv to stay updated the latest project developments.
