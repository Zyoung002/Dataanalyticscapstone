#Trends in gaming

Project Focus
To investigate trends amongst gamers of varying ages and see how they spend their time and money.
In this project we utilized many resources availble within our Visual Studio program. 
We use Pandas to help sort and clean up the data to make it easier to read and understand.
Matplotlib was used to help create visual and make them easy to see.
Jupyter Notebook is our main delivery method for this project as it allows us to set everything into a more story board presentation to walk you through the data deep dive and thought processess involved in that. 
## Project Requirements
___
1.Use a virtual environment for your project.

2.Include a requirements.txt file in your repository.

3. Read your data using one of the following methods:
From a local file
Using a public API
Through web scraping

4.Perform thorough data cleaning, including:
Handling null or missing values
Normalizing data where applicable
Renaming columns for clarity
Verifying that column data types accurately represent the data

5. Utilize 3 matplotlib visualizations.

6. Use a virtual environment.

7. Jupyter notebook is clearly anotated.

8.Store your cleaned data in a SQLite database.
Create at least two tables

9.Define a primary key for each table to allow joins
Perform a SQL join between your tables to retrieve only the data needed for your visualizations

### Virtual Environment Instructions
1. After you have cloned the repo to your machine, navigate to the project folder in GitBash/Terminal.
2. Create a virtual environment in the project folder.
3. Activate the virtual environment.
4. Install the required packages.
5. When you are done working on your repo, deactivate the virtual environment.

**Virtual environment commands**

| Command | Linux/Mac | Git Bash |
| ----------- | ----------- | ----------- |
| Create | python3 -m venv .venv | python -m venv .venv |
| Activate | source .venv/bin/activate | source .venv/Scripts/activate |
| Install | pip install -r requirements.txt| pip install -r requirements.txt|
| Deactivate | deactivate | deactivate |

Once activated you should be able to run the program in the Gaming_Trends.ipynb.

Note for VS Code Users:

If you're using VS Code to run the Jupyter Notebook or Python script, ensure that the virtual environment(venv) is selected as the kernel. This is necessary for the modules installed from requirements.txt to be active when running the project.

To select the kernel, open the Command Palette (Ctrl+Shift+P or Cmd+Shift+P on Mac) and search for "Python: Select Interpreter". Choose the one for the virtual environment (venv).





