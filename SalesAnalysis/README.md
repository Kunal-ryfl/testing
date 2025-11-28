# Sales Analysis (Java)

This project demonstrates data analysis on a CSV sales dataset using **Java Streams and functional programming**.

---

## Description

The application reads sales data from a CSV file and performs the following analyses:

- Total revenue calculation
- Quantity sold by category
- Revenue by product
- Top-selling product
- Average sale value

It demonstrates:

- Functional programming
- Stream operations
- Data aggregation
- Lambda expressions
- Reading CSV files from resources

---

## Project Structure
````
SalesAnalysis/
│── README.md
└── src/
├── main/java/
│ ├── App.java
│ ├── model/SalesRecord.java
│ └── service/SalesAnalyzer.java
├── main/resources/
│ └── sales.csv
└── test/java/
└── SalesAnalyzerTest.java
````
## Setup Instructions

1. Clone the repository:

````
git clone git@github.com:Kunal-ryfl/BuildRound.git
````
2. Open the project in IntelliJ IDEA or another Java IDE.

3. Make sure src/main/resources is marked as Resources Root.

4. Run the main class:
````
App.main()
````
5. Run unit tests from SalesAnalyzerTest.java to validate the analysis methods.

## Sample Output and Screenshots
````
=== Sales Analysis Report ===
Total Revenue: 208600.0

Quantity by Category: 
Accessories: 3
Clothing: 6
Electronics: 11

Revenue by Product: 
Laptop: 180000.0
Belt: 800.0
Shirt: 4800.0
Mouse: 4000.0
Keyboard: 6000.0
Watch: 10000.0
Pants: 3000.0

Top Selling Product: Mouse
Average Sale Value: 23177.777777777777
````
<img width="1060" height="651" alt="image" src="https://github.com/user-attachments/assets/3ccb0eb3-7c4e-4ab5-8cb9-c8adb4da1870" />

<img width="1229" height="423" alt="image" src="https://github.com/user-attachments/assets/2a33c501-ae9a-43c7-8e89-1300276b53cf" />

