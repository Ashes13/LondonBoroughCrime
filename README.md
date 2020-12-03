
## Crime Dataset Exploration
### Project definition
The objectives were to explore how crime has evolved in London boroughs through the years and use that data to accurately gauge the expected crime levels for future years. This could be used as a diagnostic measure to select policies to prevent spikes in future crimes for London boroughs.
### Data Preparation
London Crime dataset is contained with criminal year records from each borough in London where the observation begins at 2008 and ends at 2018. The criminal record is separated in major categories such as burglary, drugs and robbery. Each major category is divided into minor categories. For example, ‘Burglary’ is spilt to ‘Burglary in Other Buildings’ and ‘Burglary in a Dwelling’. Data exploration was necessary before pre-processing took place for different models. Various plots were created to investigate trends of crime throughout the last 10 years.      
                            
From figure 2, it provides information about trends of crime that occurred during 2008 to 2018. It can be noticed that overall crime rate decreased over the period of seven years between 2008 and 2014. The figure slightly declined from around 850,000 cases in 2008 to just above 800,000 cases in 2012. The total number of crimes record then went down dramatically to almost 700,00 cases in 2014. However, the graph began to rise again in 2015 and the number reached to approximate 850,000 cases in the final year of the observation.
It also can be observed that most of the crime committed between 2008 and 2018 were ‘Theft and handling’. Moreover, ‘violence against person’ is considered to happen frequently after ‘Theft and handling’. While ‘sexual offences’ crimes were the minority in the category. 
The data preparation for each model were mostly similar and used a transposed version of the original dataset to allow for classification tasks. The differences being in SVM the data was kept at a high dimension and LCS adding scores for analysis and evaluation. The subtle preparation differences mainly involved changing the way the crimes were accounted for within the years, these are elaborated on in each section.
### Assumptions 
There were not many assumptions as the data already had much clarity and was ideal for the objectives, we set ourselves. The models were largely based off factual investigation than general statements.

### Data dictionary
| Field | Description |
| --- | --- |
| Borough | Type of crime divided in major classes such as Burglary, Drugs, Robbery |
| Major Category	 | Show file differences that haven't been staged |
| Minor Category	 | Specific type of crime which split from major category |
|20xxxx	|   Year and month of the recorded. The first two digits describe the year and the last two digits describe the month. For example, ‘201804’ means the record was create in April 2018. |


