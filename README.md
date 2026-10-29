# Mini-Projects
# ⚡ Electricity Consumption Analysis System

A **C++ mini-project** that analyzes daily electricity consumption for 30 days and generates a monthly consumption report with an estimated electricity bill and a simple text-based bar chart.

## 📌 About the Project

The Electricity Consumption Analysis System is a console-based application developed using C++. It helps users understand their electricity usage by calculating total and average consumption, identifying the days with the highest and lowest usage, and comparing consumption trends over two 15-day periods.

This project demonstrates the practical use of basic C++ programming concepts.

## ✨ Features

- **Daily Data Input:** Enter electricity consumption for 30 days.
- **Total Consumption:** Calculate total units consumed during the month.
- **Average Consumption:** Calculate average daily electricity usage.
- **Highest Consumption:** Identify the day with maximum consumption.
- **Lowest Consumption:** Identify the day with minimum consumption.
- **Bill Estimation:** Estimate the electricity bill using example tariff slabs.
- **Trend Analysis:** Compare consumption during the first and last 15 days.
- **Text-Based Bar Chart:** Display daily consumption using asterisks (`*`).
- **Input Validation:** Prevent negative electricity consumption values.

## 🛠️ Technologies Used

- **Programming Language:** C++
- **Compiler:** GCC / MinGW
- **Code Editor:** Visual Studio Code
- **Concepts:** Arrays, loops, conditional statements, functions, and mathematical calculations.

## 💰 Example Electricity Tariff

The program uses the following illustrative rates to estimate the bill:

| Consumption Slab | Rate per Unit |
|---|---:|
| First 100 units | ₹4.50 |
| Next 100 units | ₹6.50 |
| Above 200 units | ₹8.00 |

**Note:** These rates are examples for academic purposes and may not match actual electricity tariffs. The estimated bill excludes additional charges.

## 🚀 How to Run the Project

### Prerequisites

Install a C++ compiler such as GCC or MinGW and a code editor such as Visual Studio Code.

### Steps

1. Clone or download this repository.
2. Open the project folder in Visual Studio Code.
3. Open the terminal in the project directory.
4. Compile the source code:

   ```bash
   g++ electricity.cpp -o electricity
   ```

5. Run the program.

   **Windows:**
   ```bash
   .\electricity.exe
   ```

   **Linux / macOS:**
   ```bash
   ./electricity
   ```

6. Enter electricity consumption in units for each of the 30 days when prompted.
7. View the monthly report, estimated bill, consumption trend, and daily bar chart.

## 📊 Sample Output

```text
========== MONTHLY REPORT ==========
Total Units: 250.00
Average Daily Units: 8.33
Highest Consumption: 15.00 units on Day 12
Lowest Consumption: 3.00 units on Day 5
Estimated Electricity Bill: Rs. 1500.00

========== CONSUMPTION TREND ==========
Consumption increased in the last 15 days.

========== DAILY BAR CHART ==========
Day  1 | **** 8.00 units
Day  2 | ****** 12.00 units
```

*Note: The values above are illustrative examples. Actual output depends on the data entered.*

## 🎯 Objectives

- Understand and analyze daily electricity consumption.
- Apply arrays and loops to process data.
- Use functions to organize and reuse code.
- Implement conditional statements for bill estimation.
- Present consumption data in a simple visual format.

## 🔮 Future Improvements

- Store daily consumption data in a CSV file.
- Read saved consumption data from a file.
- Add monthly comparisons and graphical charts.
- Use applicable local electricity tariff rates.
- Develop a graphical user interface.

## 👥 Project Type

**Academic Mini-Project — Second Year (SY) Data Science**

## 📄 License

This project is intended for educational purposes. You may add a license file if you plan to share or reuse the project publicly.

---

**If you find this project useful, consider giving the repository a ⭐ on GitHub!**
