# Stock Portfolio Tracker

# Hardcoded stock prices
stock_prices = {
    "AAPL": 180,
    "TSLA": 250,
    "GOOGL": 140,
    "MSFT": 420,
    "AMZN": 190
}

total_investment = 0

print("===== STOCK PORTFOLIO TRACKER =====")

n = int(input("Enter the number of stocks: "))

for i in range(n):
    stock_name = input("\nEnter stock name (AAPL, TSLA, GOOGL, MSFT, AMZN): ").upper()
    quantity = int(input("Enter quantity: "))

    if stock_name in stock_prices:
        investment = stock_prices[stock_name] * quantity
        total_investment += investment

        print("Price per share:", stock_prices[stock_name])
        print("Investment Value:", investment)
    else:
        print("Stock not found!")

print("\n===== PORTFOLIO SUMMARY =====")
print("Total Investment Value = $", total_investment)

# Save result to a text file
file = open("portfolio.txt", "w")
file.write("Total Investment Value = $" + str(total_investment))
file.close()

print("Portfolio saved to portfolio.txt")
