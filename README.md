# Project-1--Growth-Detective

## 📁 Project Structure
### 1. Notebook and Code- Project_1_Growth_Detective.ipynb
### 2. ReadMe file- README.md


## ▶️ Instructions to Replicate

NOTE: This project runs fully in **Google Colab** using R.

### 1. Open the Notebook
- Open: [Google Colab Link](https://colab.research.google.com/drive/19Uhs0IsJyaLhCB9I3SpQnNzov4q6Vj0Z?usp=sharing) OR click on the .ipynb file above and click on "OPEN IN COLAB" button on the top left.

### 2. Set Runtime to R
- In Colab, go to the menu bar: **Runtime → Change runtime type**  
- Under **Kernel**, select **R** instead of Python.  
- Click **Save**. 

### 2. Run All
- In Colab: Runtime → Run all
- The notebook will:
  - Collect and clean WDI & OECD data
  - Compute GDP growth rates
  - Generate visualizations (line plots, scatterplots, correlation matrix)

## 📚 Data Sources
The following datasets were used:

- **World Bank – World Development Indicators (WDI)**  
  - GDP per capita (`NY.GDP.PCAP.CD`)  
  - Population growth (`SP.POP.GROW`)  
  - FDI net inflows (`BX.KLT.DINV.CD.WD`)  
  - Life expectancy at birth (`SP.DYN.LE00.IN`)  
- **OECD Statistics** for Part 4 aggregate analysis  

Accessed via the R package **`WDI`**.



