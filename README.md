# Car Price Analysis

### Author: Maria Molebna

## Description

This project analyzes car prices to identify outliers based on the interquartile range (IQR). It groups car prices into "data" (normal values) and "outliers" (extreme values).

## Features

- Calculates Q1, Q3, and IQR for car prices.
- Identifies outliers using the formula: `Outliers = Prices < Q1 - 1.5 * IQR` or `Prices > Q3 + 1.5 * IQR`.
- Outputs the count of normal prices and outliers.

## Requirements

- **JDK 22+**
  
## How to Build and Run

### Using Command Line

1. Clone the repository:
    ```bash
    git clone https://github.com/molebna/CarPriceAnalysis.git
    cd CarPriceAnalysis
    ```

2. Compile:
    ```bash
    javac -d bin src/CarPriceAnalysis.java
    ```

3. Run:
    ```bash
    java -cp bin CarPriceAnalysis
    ```

## Example Output

```
--- Car price statistics ---
Min price: 1530.06
Max price: 183619.24
Average price: 54438.21
Standart deviation: 29538.23
--- Outliers ---
{data=493, outliers=7}
```

