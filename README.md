# Pre-processing and Analysis of Electoral Data

##Description

This project pre-processes and analyzes electoral data for the state of São Paulo. Data is efficiently manipulated to meet RAM memory constraints, including clearing names, creating auxiliary tables, and interactively viewing results.

##Step by step

1. **Data Preparation and Initial Handling**
     - Download election databases.
     - Careful pre-processing to adapt to RAM memory.
     - Exclusion of tuples not related to São Paulo.
     - Creation of auxiliary tables for municipalities, gender, age group and education level.

2. **Cleaning Names**
     - Implementation of `limpar_name` function to remove special characters.
     - Application of the function to the names of the candidates.

3. **Additional Data Handling**
     - Creation of tables for positions, types of vote, parties and candidates.
     - Mapping candidate names to a unique identifier (`ID_CANDIDATE`).
     - Optimized data export to CSV and Excel files.

4. **Interactive Data Visualization**
     - Implementation of interactive search by municipalities and candidates.
     - Use of the IPython Widgets library to create interactive elements.
     - Display of most voted candidates in municipalities and municipalities where candidates had more votes.

## Requirements

- [Python](https://www.python.org/downloads/)
- [Pandas](https://pandas.pydata.org/pandas-docs/stable/getting_started/install.html)
- [IPython Widgets](https://ipywidgets.readthedocs.io/en/stable/user_install.html)
- [Data](https://drive.google.com/file/d/1GGuBidgzo-94Bp2IOjngXPaX9rA5ZX8j/view?usp=gmail)

## Running the Project

1. Download election databases.
2. Place the data files in the same directory as the Python script.
3. Run the Python script for preprocessing and interactive visualization.
4. Watch the interactive output in the Jupyter Notebook to explore the results.

## Additional Resources

- [Pandas Documentation](https://pandas.pydata.org/pandas-docs/stable/index.html)
- [IPython Widgets Documentation](https://ipywidgets.readthedocs.io/en/stable/index.html)

## Contribution

Contributions are welcome! Feel free to open issues or submit pull requests.

##Contact

If you have questions or suggestions, please contact:

douglas
douglas.rioram04@gmail.com
