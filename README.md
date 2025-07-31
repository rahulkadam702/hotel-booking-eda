# Hotel Booking EDA (Exploratory Data Analysis)

This project analyzes hotel booking data (119,390 rows, 32 columns) to uncover key business insights, cancellations, and revenue trends for two different hotel types.

## Project Overview

- **Goal**: Explore hotel bookings and identify patterns related to cancellations, pricing (Average Daily Rate), peak months, and market segments.
- **Dataset**: Large public hotel booking dataset (2015-2017).

## Technologies Used

- `Python` (3.x)
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `Jupyter Notebook`

## Main Steps & Findings

- **Data Cleaning**: Removed unnecessary columns (`agent`, `company`) and rows with nulls for complete analysis.
- **Cancellations**:
  - Overall cancellation rate: ~37%.
  - Resort hotel: 28% canceled; City hotel: 42% canceled.
- **Revenue Trends**:
  - Visualized average daily rates (ADR) by hotel type and cancellation status over time.
- **Seasonality**:
  - Bookings and cancellations vary significantly by month.
- **Market Segments**:
  - Most bookings: Online Travel Agencies.
  - Group bookings are a major source of cancellations.

## Key Visualizations

- Reservation status counts (overall & split by hotel type)
- Box plots for ADR outliers
- Cancellation rates by hotel & month
- ADR trends over time by hotel type
- Pie chart: Top 10 countries by cancellation count

_Sample Visual:_
![Sample Chart](path/to/your/chart.png) <!-- Replace with actual image if you upload one -->

## How to Run

1. **Clone the repo** and install dependencies:
    ```
    pip install numpy pandas matplotlib seaborn
    ```
2. **Open Jupyter Notebook**:
    ```
    jupyter notebook hotel_bookings_EDA.ipynb
    ```
3. Notebook runs end-to-end with current code and data.
- If original dataset cannot be included, adjust the notebook to use a sample or describe dataset structure below.

## Data Notes

- **Source**: [Original hotel booking dataset] (delete or update if private).
- **Privacy**: Real dataset may not be shareable. If so, provide a sample or schema description.

## License

MIT License (recommendation—add LICENSE file for full text).

---

**For recruiters**: See the notebook and PDF for full analysis, code clarity, and data-driven insight.

---

