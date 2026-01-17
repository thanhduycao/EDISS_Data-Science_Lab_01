# EDISS Data Science Lab 01

A data science project focused on analyzing and merging accommodation data from multiple booking platforms (Agoda, Booking.com, and Trivago).

## Project Overview

This project involves data collection, processing, and analysis of hotel/accommodation listings from three major booking platforms. The goal is to create a unified dataset for comparative analysis and insights.

## Repository Structure

```
EDISS_Data-Science_Lab_01/
├── agoda_data.csv                          # Raw data from Agoda
├── booking_data.csv                        # Raw data from Booking.com
├── trivago_data.csv                        # Raw data from Trivago
├── merged_accommodation_all_data.csv       # Merged dataset from all platforms
├── lab01_group04.ipynb                     # Main Jupyter notebook with analysis
└── script.sh                               # Shell script for automation
```

## Data Sources

The project utilizes accommodation data from three major booking platforms:

- **Agoda** - Online travel agency specializing in Asia-Pacific
- **Booking.com** - Global accommodation booking platform
- **Trivago** - Hotel and accommodation comparison site

## Files Description

### Data Files

- `agoda_data.csv` - Contains accommodation listings scraped/collected from Agoda
- `booking_data.csv` - Contains accommodation listings from Booking.com
- `trivago_data.csv` - Contains accommodation listings from Trivago
- `merged_accommodation_all_data.csv` - Consolidated dataset combining all three sources

### Analysis

- `lab01_group04.ipynb` - Jupyter notebook containing:
  - Data loading and preprocessing
  - Exploratory data analysis (EDA)
  - Data merging and integration
  - Visualizations and insights
  - Statistical analysis

### Automation

- `script.sh` - Shell script for automating data processing tasks

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Required Python libraries (pandas, numpy, matplotlib, seaborn, etc.)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/thanhduycao/EDISS_Data-Science_Lab_01.git
cd EDISS_Data-Science_Lab_01
```

2. Install required dependencies:
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook lab01_group04.ipynb
```

## Usage

### Running the Analysis

1. Open the Jupyter notebook `lab01_group04.ipynb`
2. Run cells sequentially to:
   - Load data from individual CSV files
   - Clean and preprocess the data
   - Merge datasets
   - Perform exploratory analysis
   - Generate visualizations


## Data Analysis

The project includes analysis of:

- Accommodation prices across platforms
- Rating comparisons
- Location distribution
- Amenities and features
- Platform-specific trends
- Data quality and completeness

## Group Information

**Group 04** - EDISS Data Science Lab

## Project Status

This is an academic project for the EDISS (likely European Data and Information Systems Science) program.

## License

This project is part of an academic assignment. Please check with the repository owner for usage rights.

## Contributing

This is an educational project. For questions or suggestions, please contact the repository owner.

## Contact

Repository maintained by: [@thanhduycao](https://github.com/thanhduycao)

---

*Note: This is a lab assignment project. The data and analysis are for educational purposes.*
