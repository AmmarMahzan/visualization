### Visualization 1: Ticket Sales and Redemptions Over Time

- **Software Used:** Python (Jupyter Notebook – pandas and matplotlib)
- **Intended Audience:** General public, Toronto ferry users, and city planners
- **Message:**  
  This line plot shows the trends of ticket sales and redemptions over time using 15-minute intervals. It reveals seasonal patterns and periods of peak usage that can inform ferry scheduling and operations planning.
- **Design Considerations:**
  - Distinctive colors (blue for Sales Count, orange for Redemption Count)
  - Rotated x-axis timestamps for better readability
  - Gridlines for visual clarity
  - High-resolution export (300 dpi)
- **Reproducibility:**  
  The full data cleaning and plotting process is documented in the Jupyter Notebook file `Assigment_3.ipynb`, using open-source libraries (`pandas`, `matplotlib`). Anyone can reproduce the figure using the same dataset and code.
- **Accessibility:**  
  Used accessible color palette, readable axis labels and legend, and exported a high-resolution figure.
- **Communities Impacted:**
  - Ferry passengers
  - Event planners
  - City transit authorities
- **Features Included/Excluded:**  
  Used only `Timestamp`, `Sales Count`, and `Redemption Count`. The `_id` column was excluded as it adds no analytical value.
- **Underwater Labour:**  
  Parsing timestamps, organizing and aggregating large amounts of data, resolving overlapping data points, formatting the plot, and writing well-commented reproducible code.
