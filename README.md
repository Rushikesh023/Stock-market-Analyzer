# Stock-market-Analyzer
Our project is to analyze stock prices and current marke trend and scenario
# 📊 Stock Market Analyzer  

A simple C-based console application to manage and analyze stock data. This project allows users to add, view, and analyze stock information such as opening and closing prices. It demonstrates key programming concepts like **structures**, **linked lists**, and **basic data analysis** in C.  

---

## 🧠 Project Overview  

The **Stock Market Analyzer** helps users store stock details (like company name, opening price, and closing price) and perform basic operations such as:  
- Adding new stock records  
- Displaying stock data  
- Calculating profit or loss  
- Finding the highest and lowest performing stocks  

This mini-project is ideal for students learning **Data Structures in C**.  

---

## ⚙️ Features  

- ➕ **Add New Stock** – Insert details for a company’s stock (name, opening price, closing price).  
- 📋 **Display All Stocks** – View all stock entries in a structured format.  
- 💹 **Profit/Loss Analysis** – Determine gain or loss for each stock.  
- 🏆 **Top Performer** – Identify the stock with the maximum profit.  
- 📉 **Lowest Performer** – Identify the stock with the highest loss.  
- ❌ **Exit Option** – Gracefully terminate the program.  

---

## 🧩 Data Structure Used  

- **Structure (`struct`)** for storing stock details  
- **Linked List** for dynamic data storage and traversal  

```c
typedef struct Stock {
    char name[50];
    float open, close;
    struct Stock *next;
} Stock;
