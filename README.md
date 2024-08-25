# Chat With Your DataFrame
Here's a quick guide on querying your data, particularly from CSV and Excel files, to obtain accurate results, perform statistical analysis, and create visualizations.


## Approaches
### 1.With PandasAI Module
PandasAI is a Python package that makes it easy to ask questions to your data in natural language. It helps non-technical users to interact with their data in a more natural way, and it helps technical users to save time and effort when working with data.

**Usage:**

- **Install Packages**

      !pip install -q pandasai

- Import necessary libraries
- Read Dataframe
- **Environment Setup:**
  The PANDASAI_API_KEY is set as an environment variable using the os.environ method. Replace "Api key" with your actual PandasAI API key.
  
      import os
      os.environ["PANDASAI_API_KEY"] = "API-KEY"

- Initialize the OpenAI LLM with the API token stored in the environment variable.
- Wrap the DataFrame with PandasAI's SmartDataframe to enable AI-driven queries.
- Use natural language to query the data




