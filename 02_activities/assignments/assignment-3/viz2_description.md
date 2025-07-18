### Visualization 2: Average Ticket Sales and Redemptions by Hour

- **Software Used:** Tableau Public
- **Intended Audience:** Toronto ferry users, tourists, and city transit planners
- **Message:**  
  This side-by-side bar chart visualizes the average ticket sales and redemptions per hour of the day. It clearly shows the most active hours for ferry operations and can help optimize scheduling and user flow.
- **Design Considerations:**
  - Color-coded bars (orange for Sales Count, blue for Redemption Count)
  - Dual-axis chart to separate the two measures clearly
  - Clean font, descriptive title, and labeled axes
- **Reproducibility:**  
  The chart was built in Tableau Public using the original dataset. A new calculated field was created to extract the hour:  
  `Hour = DATEPART('hour', DATETIME([Timestamp]))`.  
  Steps are documented and reproducible using Tableau.
- **Accessibility:**  
  Accessible color scheme, simple layout, readable font size, and high-resolution PNG export.
- **Communities Impacted:**
  - Ferry staff (e.g., kiosk operators, crew scheduling)
  - Public transit decision-makers
  - Commuters planning trips to avoid peak hours
- **Features Included/Excluded:**  
  Used `Timestamp`, `Sales Count`, and `Redemption Count`, with focus on hourly aggregation. Excluded `_id` and granular time resolution to simplify insights.
- **Underwater Labour:**  
  Creating calculated fields in Tableau, exploring layout options, adjusting dual-axis views, and fine-tuning visual appearance before exporting the chart.
