# **Portfolio Tracker**

### **Description**
**Portfolio Tracker** is an interactive trading simulator that allows users to manage multiple assets, track cash flow, and visualize portfolio performance over time. It provides a simple way to practice buying and selling assets while calculating profits and accounting for transaction fees. This project is ideal for learning portfolio management and investment tracking concepts.

---

## **Features**
- **Multiple Asset Management**: Manage any number of assets simultaneously.
- **Transaction Fees**: Automatically deducts 0.75% per transaction.
- **Transaction Logs**: Records all buy and sell transactions.
- **Error Handling**: Prevents overspending or selling more than available.
- **Portfolio Visualization**: Plots changes in portfolio value over time.
- **Interactive Menu**: User-friendly interface to simulate trades.

---

## **Prerequisites**
- Python 3.x  
- `matplotlib` (for plotting graphs)

To install the necessary package, run:
```bash
pip install matplotlib
```

---

## **How to Run Portfolio Tracker**

### **Option 1: Run on Google Colab**
1. Open [Google Colab](https://colab.research.google.com/).
2. Create a new Python notebook.
3. Copy the project code and paste it into a code cell.
4. Click **Run** to start the simulator.

### **Option 2: Run Locally**
1. Clone or download the repository:
   ```bash
   git clone https://github.com/your-username/portfolio-tracker.git
   ```
2. Navigate into the project directory:
   ```bash
   cd portfolio-tracker
   ```
3. Install the dependencies:
   ```bash
   pip install matplotlib
   ```
4. Run the project:
   ```bash
   python portfolio_tracker.py
   ```

---

## **Usage Instructions**
When the code runs, the following menu will appear:

```
1. Buy Asset
2. Sell Asset
3. View Portfolio
4. View Transaction Log
5. Plot Portfolio Value
6. Exit
```

- **Option 1**: Enter the asset name, quantity, and price to buy.
- **Option 2**: Enter the asset name, quantity, and price to sell.
- **Option 3**: View the current portfolio and available cash.
- **Option 4**: View the transaction log of all trades.
- **Option 5**: Plot a graph showing the portfolio’s value over time.
- **Option 6**: Exit the simulation.

---

## **Example Run**

```
1. Buy Asset
Enter asset name: AAPL
Enter quantity: 5
Enter price per unit: 150
Bought 5 units of AAPL at $150 each.

3. View Portfolio
Current Portfolio:
AAPL: 5 units
Available Money: $596.25
```

---

## **Project Structure**

```
Portfolio-Tracker/
│
├── portfolio_tracker.py  # Main script
└── README.md             # Documentation
```

---

## **How the Code Works**
1. **Buying Assets**: Deducts money and adds the quantity to the portfolio.
2. **Selling Assets**: Increases cash by the sold value, accounting for transaction fees.
3. **Transaction Logs**: Records each transaction for review.
4. **Portfolio Visualization**: Plots the portfolio value over time.
5. **Error Handling**: Ensures valid transactions (no overspending or overselling).

---

## **Technologies Used**
- **Python 3.x**: Core programming language.
- **Matplotlib**: For graphing portfolio value over time.

---

## **Future Improvements**
- **API Integration**: Use real-time data from finance APIs.
- **CSV Export**: Save the transaction logs to a file.
- **Risk Management**: Implement stop-loss and take-profit orders.
- **GUI Development**: Create a graphical user interface for easier use.

---

## **Contributing**
Contributions are welcome! Please fork the repository and submit a pull request with your changes.

---

## **License**
This project is licensed under the **MIT License**. See the `LICENSE` file for more details.

---

## **Acknowledgments**
This project was inspired by the need for a simple, educational trading simulation tool. Special thanks to the open-source community for their valuable resources and support.

---

Enjoy using **Portfolio Tracker**! 🚀

---

### **How to Add This to GitHub**
1. Create a new repository on GitHub.
2. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/your-username/portfolio-tracker.git
   ```
3. Navigate into the project folder:
   ```bash
   cd portfolio-tracker
   ```
4. Add the README.md file:
   ```bash
   touch README.md
   ```
5. Open the README.md file and paste this content into it.
6. Stage, commit, and push your changes:
   ```bash
   git add README.md
   git commit -m "Added README"
   git push origin main
   ```

---

This is now ready for **GitHub**! Let me know if you need any further help.
