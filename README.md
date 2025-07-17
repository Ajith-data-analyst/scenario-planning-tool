# Scenario Planning Tool

This Excel-based tool helps analyze financial scenarios for product sales. It calculates key financial metrics under three different scenarios: Best Case, Realistic, and Worst Case.

## 📋 Key Parameters
| Parameter         | Value      |
|-------------------|------------|
| Customer          | Croma      |
| Product(s)        | Mouse      |
| Date              | 2025-05-01 |
| Discount          | 10%        |
| COGS              | 30%        |
| Average NIP       | 6          |
| GM Target         | 100,000    |

## 📊 Scenario Analysis
The tool calculates the following metrics for each scenario:

| Metric              | Formula (Best Case Example)      |
|---------------------|----------------------------------|
| Sales Unit          | Manual input                    |
| Net Invoice Sales   | `= Sales Unit * Price per Unit` |
| Post Discount       | `= Net Invoice Sales * Discount` |
| Net Sales           | `= Net Invoice Sales - Post Discount` |
| COGS                | `= Net Sales * COGS Rate`        |
| Gross Margin        | `= Net Sales - COGS`             |
| vs Target           | `= Gross Margin - GM Target`     |

## 🔍 Scenarios Evaluated
1. **Best Case Scenario**  
   - Sales Unit: 100,000
   
2. **Realistic Scenario**  
   - Sales Unit: 50,000
   
3. **Worst Case Scenario**  
   - Sales Unit: 25,000

## 💻 Usage Instructions
1. Update yellow-highlighted parameters as needed
2. Modify scenario inputs (Sales Units)
3. Review automatically calculated financial metrics
4. Compare results across scenarios

