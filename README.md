# Harvard Artifact Dashboard
An interactive data app that lets you explore fascinating artifacts from the Harvard Art Museums using modern data tools.
Built with Python, MySQL, and Streamlit, this project bridges art, history, and data in a single elegant interface.

## ✨ Features

- Data Extraction (ETL): Fetches artifact data from the Harvard Art Museums API.
- MySQL Integration: Stores data locally for efficient querying and analysis.
- Streamlit Dashboard: Clean and user-friendly interface to view and explore artifacts.
- Interactive Filtering: Filter artifacts by classification, culture, or date range.

## 🧰 Tech Stack

- Python 3.12+
- Streamlit – for building the web app
- MySQL – for storing artifact data
- Pandas – for data cleaning and analysis

## ⚙️ Installation & Setup

### Clone this repository
```
https://github.com/adhunasyed-cmd/Harvard-Artifact-Dashboard.git
```

### Install dependencies manually
install these packages:
```
pip install streamlit pandas requests mysql-connector-python
```

### Set up MySQL database

Make sure MySQL is running and create a database named:
```
CREATE DATABASE harvard_artifacts;
```

### Update your connection details inside the code:

```
connection = mysql.connector.connect(
    host="127.0.0.1",
    user="yourusername",
    password="yourpassword",
    database="harvard_artifacts"
)
```

### Run the Streamlit app
```
streamlit run app.py
```
## 🧠 Inspiration

This project celebrates how data science and art can merge to create something both analytical and aesthetic.
Every dataset tells a story — and this one tells centuries of human creativity. 🎨
