# OpenDataSet
Comprehensive data from nearly 200 colleges and universities, compiled from trusted sources including the Common Data Set and IPEDS database.

Some of the most important data on Colleges and Universities in the US is too hard to access. Sometimes it can take multiple Google searches just to find a school's CDS. Let alone studying and analyzing CDS data on a larger scale since it's in a PDF format. This is why Petersons among others charge for this data. The ODS has the goal of freeing and enabling the analysis of it.

**Data Sources**

The data in the ODS is from the 2023-24 admissions cycle or whatever latest CDS was avaliable.
To ensure that there is a comprehensive amount of accurate data, I compiled data from a variety of sources, mostly the IPEDS database and the CDS.

Common Data Set (CDS)
* The Common Data Set initative has been jointly developed by data giants Petersons, US News & World Report, and the College Board to help standardize data definitions. Schools vouluntarily participate. It includes data including admissions, enrollment, academic programming, as well as other extracarricular statistics. To make this data more accessable, I had to train a GCP Document AI model to parse documents and extract data.
* Green cells in the excel file

IPEDS Database
* The Integrated Postsecondary Education Data System has been facilitated by National Center for Education Statistics. Schools are mandated to participate if they want federal aid. The data is mostly limited in scope compared to the CDS, but much easier to access. There are some unique numbers that the IPEDS has that CDS doesn't, like endowment statistics. If you Google a college, this is where the data comes from!
* Blue cells in the excel file

US News & World Report Rankings
* In addition to the other sources listed, I also pulled the US News rankings for each college. This can be helpful if one is trying to make an app or website to help judge colleges and enables the ability to put rankings on that page. Obviously, US News rankings should not be considered the end all be all.
* Yellow cells in the excel file
