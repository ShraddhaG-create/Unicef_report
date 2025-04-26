# UNICEF World Issue Report

This project analyzes global challenges in **clean water access**, **child health**, and **economic development** using real-world UNICEF datasets.

The report includes **interactive charts**, **trend analyses**, and **policy insights**. It was created using **Python**, **Seaborn**, **GeoPandas**, and **Quarto**.

---

## Project Structure
```plaintext
├── README.md            
├── requirements.txt     
├── test.py              
├── unicef_final.qmd      
├── unicef_final.html     
├── unicef.qmd            
├── unicef.html           
├── unicef_indicator_1.csv  
├── unicef_indicator_2.csv  
├── unicef_metadata.csv  
```

---

## How to Set Up and Run

### Clone the Repository:
```bash
git clone "url"
cd unicef-report
```

### Create a Virtual Environment:
```bash
python -m venv report
```

### Activate the Environment:
- **On Windows:**
  ```bash
  report\Scripts\activate
  ```
- **On Mac/Linux:**
  ```bash
  source report/bin/activate
  ```

### Install Required Packages:
```bash
pip install -r requirements.txt
```

### Render the Report:
Make sure Quarto is installed ([Installation Guide](https://quarto.org/docs/get-started/)).

Then render the report:
```bash
quarto render unicef_final.qmd
```

This will generate `unicef_final.html` which you can open in your browser.

---

## Requirements

The environment uses the following Python packages:
- pandas
- geopandas
- matplotlib
- seaborn
- pyogrio
- scikit-learn

You can install them individually if needed:
```bash
pip install pandas geopandas matplotlib seaborn pyogrio scikit-learn
```

---

## Key Features

- **Global Map Visualization**: Access to safe water by country
- **Bar Charts**: Top countries with highest/lowest water access
- **Regression Analysis**: GDP per capita vs Water Access
- **Distribution Graphs**: Birth rates, water access spread
- ⏱**Time Series**: Global progress over time

Each graph includes:
- Clear **titles** and **captions**
- **Legends** and **color scales** explained
- **Real-world interpretation** linked to UNICEF goals

---

## Hosting Information

This repository and project are hosted on **GitHub**:

**GitHub Repository Link**: ---

---

## Credits

Developed by **Data Analyst - UNICEF**  
Dataset Source: [UNICEF Data Portal](https://data.unicef.org/)

---

## Notes

- Always activate your `report` virtual environment before running Python or Quarto commands.
- Some charts (like the world map) fetch external files and may need internet access.
- Bonus improvements like regression equations and peak markers are included.

---


