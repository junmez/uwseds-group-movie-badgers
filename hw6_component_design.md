# Component Design

The component design document should have the following sections:
- Component list. 
  - Access movie_id from TMDB
  - Get movie_information from OMDB
  - Combine movie_id and movie_information and save as .csv
  - Conduct missing value imputation
  - Visualize features
  - Extract features
  - Perform regression models
  - Compare regression models
  - Deploy analysis result to WebUI
  - ...
  
- Component specifications. For each component, you should have a section that specifies:
  - What it does. This should be a high level description of the roles of the component.
  - Name. This should be the name that you use in the component's implementation (e.g., the name of a python class or function).
  - Inputs. Be specific about the data types. For DataFrames, specify the column names and the types of the column values.
  - Outputs. Same consideration as with inputs.
  - How it works (ideally with pseudo code).