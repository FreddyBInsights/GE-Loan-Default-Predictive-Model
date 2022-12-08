# GE-Loan-Default-Predictive-Model
Development of a predictive analytic program which identifies key loan default indicators and whether a customer is likely to default on their loan.

USE CASE

Credit/Financing Risk
In response to the financial crisis of 2008–2009, the credit branch has been asked to reassess the method used to determine if an application presents a bad credit risk. The example file has data on 1,000 past credit applicants, described by 31 variables. The goal is to determine the likelihood of default for a new credit application based on a subset of the 31 variables. The business user will use this model to help determine the risk associated with extending the credit applicant credit, based on the data provided on the application. The impact of the dollar loss to the company on the default of a customer loan is 150% of the remaining balance.

The current data environment is an Excel spreadsheet that contains information about the active credit applicants assigned to a business user. The spreadsheet allows the business user to adjust the values of certain variables like loan amount to generate the scenario-based predictive likelihood that the customer will default. The model will run nightly for all loan applicants and current loan holders with reports generated for high-risk loan applicants/holders.

The data is stored in an Oracle database in transactional form. The IT department has built a data warehouse that is updated each evening with the current day data. The credit team uses this data warehouse data as the source for their reports and has the ability to have an ad hoc extract to select data into Excel for their unique research needs. The credit team extracts are limited in rows as well as fields that have been corporately pre-approved for extraction.

GE has compiled a file for the purpose of this pilot project using the extract tool. The dataset provided, Credit Data (XLS), includes information on credit applicants which the GE credit team believes to be relevant to analyzing this problem.

The credit team would like to determine if this data can be used to identify credit default of loan applicants. It is important to be able to understand loan default drivers for metadata like salary, interest rates, and other pertinent groupings which come from the analysis.

The pilot will need to only show basis for this data to be able to describe and generally identify credit applicants that may default. The management team expects to make a GO or NO GO business decision based on the pilot recommendation. If there is a GO, then GE will allocate new project dollars to arrange for GE resources to develop a full-enterprise deployed predictive analytic model. Note that the results of this pilot will be used as a basis for that next project.
 
