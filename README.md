# H1B_Hub
<ol>
<li>Extract H-1B Employer Data Hub data from USCIS.gov.</li>
<li>Transform into a single tidy compressed CSV file (located in h1b_hub_data.zip) for Load.</li>
</ol>

## Getting Started

Run H1B_Hub.ipynb in a Jupyter Notebook with Python 3 or newer.

### Prerequisites

You will need

* Web browser
* Jupyter Notebooks (or another way to run Python 3 or newer)
* pandas library: https://pandas.pydata.org/


## Additional Documentation and Acknowledgments

* Source Data: USCIS H-1B Employer Data Hub Files<br/>
https://www.uscis.gov/tools/reports-and-studies/h-1b-employer-data-hub/h-1b-employer-data-hub-files

* Metadata: Understanding Our H-1B Employer Data Hub<br/>
https://www.uscis.gov/tools/reports-and-studies/h-1b-employer-data-hub/understanding-our-h-1b-employer-data-hub

  Excerpts:
  
  "Data entry and petitioner errors may result in a missing and/or erroneous employer name, tax ID, state, city, or ZIP code in our electronic systems."

  "We anticipate updating the H-1B Employer Data Hub quarterly and providing downloadable data files. For example, data for the first quarter (October-December) of a fiscal year will be provided in April of the fiscal year."

  "NAICS code 99 means the industry is unknown. Any petition that had a blank code was assigned as 99 as well."


* Form I-129 PDF: Petition for a Nonimmigrant Worker <br/>
https://www.uscis.gov/sites/default/files/document/forms/i-129.pdf

  Excerpts:
  
  "State indicated in the mailing address of the employer and is not necessarily the beneficiary(ies) work location"
  
* North American Industry Classification System - NAICS <br/>
https://www.census.gov/naics/

* Sample data visualization on Tableau Public <br/>
https://public.tableau.com/views/USCISH-1BEmployerDataHub/USCISH-1BEmployerDataHub?:language=en-US&:display_count=n&:origin=viz_share_link
