# Hotel Booking Analytics

## Project Overview

This project analyses hotel booking data using Python to identify patterns in
booking behaviour, cancellation risk, customer segmentation, seasonality,
distribution channels, and revenue-related metrics.

The objective is to transform raw hotel booking data into actionable business
insights that can support hotel operations, customer retention, pricing, and
booking-channel strategy.

## Dataset

The original dataset contained **119,390 booking records**.

After data cleaning and duplicate removal, the final analytical dataset
contained **87,396 bookings**.

Key preparation steps included:

- Handling missing values
- Correcting data types
- Removing duplicate records
- Creating analytical features
- Preparing customer and booking segments
- Validating the cleaned dataset

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Analysis Performed

The project covers:

- Data cleaning and preprocessing
- Descriptive statistics
- Exploratory data analysis
- Booking seasonality
- Cancellation analysis
- Lead-time analysis
- Customer segmentation
- Domestic vs international guest behaviour
- Market-segment analysis
- Distribution-channel analysis
- Average Daily Rate (ADR) analysis
- Repeat-guest behaviour
- Special-request analysis
- Room-allocation analysis
- Business recommendations

## Key Findings

### Booking Seasonality

**August** recorded the highest booking volume with approximately
**11,257 bookings**.

This indicates strong summer seasonality and highlights the importance of
staffing, inventory planning, and pricing strategy during peak periods.

### Cancellation Risk

The overall cancellation rate in the cleaned dataset was approximately
**27.5%**.

Bookings with longer lead times demonstrated substantially higher cancellation
risk.

Average lead time:

- Retained bookings: **70.1 days**
- Cancelled bookings: **105.7 days**

This suggests that lead time can be used as an early warning indicator for
booking cancellation risk.

### Special Requests

Bookings containing special requests showed lower cancellation rates:

- With special request: **21.7%**
- Without special request: **33.2%**

Special requests may therefore act as a useful indicator of guest engagement.

### Domestic vs International Guests

Cancellation behaviour differed between guest-origin groups:

- Domestic cancellation rate: **35.7%**
- International cancellation rate: **23.9%**

This suggests that customer-origin segmentation can support more targeted
retention and communication strategies.

### Distribution Channels

The **GDS** channel recorded the highest average ADR at approximately
**120.3**.

Channel performance should therefore be evaluated using a combination of ADR,
booking volume, acquisition cost, and cancellation behaviour.

### Repeat Guests

Repeat guests booked much closer to their arrival date than new guests.

Average lead time:

- New guests: **82.4 days**
- Repeat guests: **17.2 days**

This provides useful insight for loyalty campaigns and short-lead promotional
strategies.

## Business Recommendations

1. Target long-lead bookings with reconfirmation messages and appropriate
   deposit strategies.
2. Encourage pre-arrival engagement and special requests.
3. Evaluate distribution channels using retained revenue and cancellation
   behaviour rather than booking volume alone.
4. Use differentiated strategies for new, repeat, domestic, and international
   guests.
5. Plan staffing, inventory, and pricing around seasonal demand peaks.

## Repository Contents

```text
hotel-booking-analytics/
├── Hotel_Booking_Analysis.ipynb
├── Hotel_Booking_Analysis.pptx
├── hotel_bookings.csv
├── README.md
├── .gitignore
└── LICENSE
