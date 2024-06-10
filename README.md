# Connecting and Manipulating PostgreSQL with Python

This repository contains a Jupyter Notebook with examples of how to connect Python with PostgreSQL and how to create and manipulate tables in PostgreSQL using Python.

## Content

- **Connection to PostgreSQL**: Examples of how to establish a connection with a PostgreSQL database using `psycopg2` and `SQLAlchemy`.
- **Loading Data into a DataFrame**: How to load data from PostgreSQL into a Pandas DataFrame.
- **Data Manipulation**: Examples of data manipulation using Pandas.
- **Creating Tables in PostgreSQL**: How to create new tables in PostgreSQL from manipulated DataFrames.
- **Credential Management**: Using a `.env` file to manage credentials securely.

## Requirements

-Python 3.x
- Jupyter Notebook
- Pandas
- psycopg2
-SQLAlchemy
- python-dotenv

## Facility

1. Clone this repository:

 ```bash
 git clone https://github.com/Mgobeaalcoba/python_postgresql
 ```

2. Create a virtual environment and install dependencies:

 ```bash
 python -m venv venv
 source venv/bin/activate # On Windows use `venv\Scripts\activate`
 pip install -r requirements.txt
 ```

3. Create a `.env` file in the project root directory with the following content, replacing the values ​​with your PostgreSQL credentials:

 ```bash
 POSTGRES_DB=database_name
 POSTGRES_USER=user_name
 POSTGRES_PASSWORD=your_password
 POSTGRES_HOST=localhost
 POSTGRES_PORT=5432
 ```

4. Start Jupyter Notebook:

 ```bash
 jupyter notebook
 ```

5. Open the `conexión de jupyter a postgres sql.ipynb` notebook and follow the examples.

## Use

The notebook includes detailed examples on how to:

- Connect to a PostgreSQL database.
- Execute SQL queries and load the results into a Pandas DataFrame.
- Manipulate the data in the DataFrame.
- Create a new table in PostgreSQL and save the manipulated data in it.

## Grades

- Make sure the `.env` file is in your `.gitignore` to avoid uploading your credentials to the repository.
- Review and adjust configurations and credentials based on your development and production environment.

## Contributions

Contributions are welcome! Feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
