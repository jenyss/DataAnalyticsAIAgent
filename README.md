# Data Analytics AI Agent based on LangChain

This is an AI Agent based on the Reason-Action pattern, designed to let you ask questions about your spreadsheets and receive either a text-based answer or a visualization, depending on how your question is formulated. The 

If you have any questions or would like to collaborate, feel free to reach out to me on [LinkedIn](https://www.linkedin.com/in/jenya-stoeva-60477249/). You're more than welcome!

## Agent Tools
* **Preview Excel Structure** – Analyzes the spreadsheet to extract column names, data types, and sample data, providing an overview of the dataset.
* **Simple Dataframe Query** – Executes basic queries to filter, sort, and retrieve specific data from the spreadsheet.
* **Complex DuckDB Query** – Processes complex queries using SQL to perform aggregations, calculations, and in-depth data analysis.
* **Create Visualization** – Generates charts and graphs to represent data visually, making trends and patterns easier to interpret.

## Execution Output 
Can be seen in the Jupyter Notebook.

## Intallation

<b>Prerequisites</b>

* Access to <b>JupyterLab, Google Colab</b>, or another interactive computing environment to run this Jupyter Notebook.

### Step 1: Clone the Repository

Clone this repository to your local machine:
```
git clone <REPOSITORY_URL>
cd <PROJECT_FOLDER>
```

### Step 2: Open Jupyter Notebook in JupyterLab

Ensure that ```<PROJECT_FOLDER>``` is accessible in JupyterLab by setting it as your working directory in JupyterLab.
 * In JupyterLab, use the "Open from Path" option to load ```DataAnalyticsAIAgent.ipynb```.
 * Similarly, load ```.env``` and populate the variable keys with appropriate values.
 * The first cell in the Notebook installs the required libraries: **%%pip install langchain langgraph pandas python-dotenv duckdb numpy**

### Step 3: Run the Jupyter Notebook

To execute the notebook, select each cell and press ```Shift + Enter```.

