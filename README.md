### ***Process to Fuzzy Match Company Names between 2 Data Source***

***Why is this useful?***
  * Company names can vary between data sources for a number of reasons - including data collection processes (e.g. free-form text boxes), naming convensions, and more.
  * This workful can help normalize company names that maintain slight differences

### What does the workflow do?
  * The majority of the work is done through phonetic matching of names
    * Additionally, the workflow will search for Acronyms and will generally be able to handle abbreviations.
    
[View the notebook](https://nbviewer.jupyter.org/github/dez9812/company-name-fuzzy-match/blob/master/Fuzzy%20Match%20-%20Company%20Name%20Workflow.ipynb)

### In-Progress
  * Fix Required: Final output is stripped original company name [e.g. H R Block instead of H&R Block]

***Fuzzy Matching is never perfect, but makes sense in some cases where perfection may not be required. Consider the use case before leveraging this workflow*** 
