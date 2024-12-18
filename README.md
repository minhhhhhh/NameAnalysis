# Baby Names Analysis

This project analyzes baby name trends from 1880 to 2014 using Python libraries. It includes tasks such as data extraction, cleaning, grouping, and visualization, culminating in identifying and plotting trends for unisex names.

---

## Features

- **Data Extraction:**
  - Unzips and loads annual baby name data from a compressed `names.zip` file.
  - Processes `.txt` files containing baby names, sex, and occurrence counts into a unified DataFrame.
- **Data Aggregation:**
  - Computes the total usage of names by gender.
  - Identifies unisex names based on a specific ratio threshold.
- **Visualization:**
  - Generates plots of name popularity over the years.
  - Compares trends for unisex names for both genders.

---

## Installation

1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd baby_names_analysis
   ```

2. Install required dependencies:
   ```bash
   pip install pandas matplotlib
   ```

3. Ensure the following data files are available:
   - `names.zip` (contains `.txt` files for annual baby names data)

---

## Usage

1. Extract the baby names data:
   ```python
   import zipfile
   zipfile.ZipFile('names.zip').extractall('.')
   ```

2. Run the Jupyter Notebook to:
   - Process and analyze baby name data.
   - Compute totals and ratios.
   - Plot popularity trends for the top unisex names.

3. Adjust file paths or analysis parameters in the code as needed.

---

## Dependencies

- **Python 3.6+**
- Libraries:
  - `pandas`
  - `matplotlib`

---

## Output Examples

- DataFrames showing aggregated data by gender and year.
- Top 10 unisex names with usage statistics.
- Plots comparing unisex name popularity over the years.

---

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests for improvements.

---

