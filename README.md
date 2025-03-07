## smart analysis 

### Project Overview
- This is a project that utilizes LLM (large language models) for data analysis. It can generate SQL queries through prompt engineering to retrieve data, helping you generate charts and answer relevant questions you propose.

### How To Use：

1. ```bash 
   pip install -r requirements.txt
    ```
2. ```bash 
   python main.py --openai_key your_key    
   ```
- **Upload data**：Begin by uploading one or more CSV files. These files will be used for generating SQL queries and subsequent analysis.

- **Explore Data Schema**: : Upon uploading data, the system generates a description of the schema, allowing users to understand the structure of their data for better insights and query formulation.

- **Ask Questions**: Describe the data you want to query in the provided textbox.

- **View Reports and Visualizations**: The system will generate SQL queries based on your description, fetch the data, debug the sql and regenerate until there is no errors, create visualizations, and present a detailed report.
 
 ### Workflow
 This project is designed with a workflow in mind, ensuring a structured approach to data analysis:

  1. **Data Upload**: CSV files are uploaded for processing.

  2. **Data Schema Generation**: The system generates a schema description to help users understand the data structure.

  3. **Query Description**: Users describe the data they want to analyze in natural language.
  
  4. **SQL Query Generation**: The system generates SQL queries based on the description.
  
  5. **SQL Execution**: Queries are executed on the uploaded data to fetch relevant information.
  
  6. **Report and Visualization**: The system generates detailed reports and visualizations from the fetched data.
  
  7. **Error Handling**: If there are SQL errors, the system provides suggestions for correction.
  
  8. **Final Report**: Users receive a comprehensive report, including SQL queries used, retrieved data, and visualizations.

  ### Dependencies

- openai: OpenAI Python SDK for interfacing with GPT-3.5 Turbo.
- pandas: For data manipulation and analysis.
- pandasql: For running SQL queries on DataFrame objects.
- gradio: For creating the user interface.


### Suggestions and Issues

- I hope this project can be helpful to you. Of course, if you have any ideas or questions, please feel free to contact me through the issues. Thank you!