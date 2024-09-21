# Geospatial Analysis of Financial Trends in Nepalese Municipalities

This project performs a **geospatial analysis** of financial trends across municipalities in Nepal. By merging financial data with geospatial data, it visualizes key economic indicators such as **average income**, **loan defaults**, and **property prices** across different districts.

The main goal of the project is to provide insights into the distribution of these financial metrics across regions, helping to identify spatial patterns that could inform policy decisions and regional financial strategies.

---

## Installation

To run the project, you'll need Python 3.x installed along with several Python libraries.

### Required Libraries:
- `geopandas`: For handling geospatial data.
- `pandas`: For data manipulation.
- `matplotlib`: For visualizing data.
- `shapely`: (If needed for geometry operations).

---

## Dataset Description

### The project uses two datasets:

#### Geospatial Data:
- **Municipality Boundaries**: A shapefile or GeoJSON file containing the geographic boundaries of municipalities in Nepal. It includes attributes like province, district, and municipality type.

#### Financial Data:
- **District-Level Financial Metrics**: A dataset with financial information such as **average income**, **loan defaults**, and **property prices** for each district.

### Data Merging:
The datasets are merged on the `DISTRICT` column, allowing us to spatially analyze financial trends across Nepal’s municipalities.

---

## Analysis

### Data Cleaning:
- Standardized district names by converting them to uppercase to ensure consistency between datasets.
- Merged the financial data with the geospatial data to create a combined dataset for analysis.

### Geospatial Visualization:
Using the merged dataset, we visualize:
- **Average Income**: Color-coded maps showing income distribution across districts.
- **Loan Defaults**: Maps representing default percentages in each region.
- **Property Prices**: Visualizing regional variations in property values.

---

## Visualizations

1. **Average Income by District**:  
   A map showing how average income varies across Nepal’s districts. Higher income districts are shown in darker shades.

2. **Loan Defaults by District**:  
   A map depicting loan default rates across districts. Darker shades indicate regions with higher default percentages.

3. **Property Prices by District**:  
   This map shows the distribution of property prices, with higher property values represented by darker colors.

---

## Results

The analysis highlights some key patterns:
- **Higher-income districts** are clustered in certain regions.
- **Loan default rates** show significant regional variations, potentially indicating economic stress in specific areas.
- **Property prices** are higher in urbanized districts, reflecting demand and regional development.

---

## Conclusion

This geospatial analysis provides a deeper understanding of how financial metrics vary across Nepal. The results can help guide policy decisions and regional development strategies by focusing on areas of economic disparity.

