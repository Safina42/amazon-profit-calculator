# amazon-profit-calculator
Amazon FBA profit calculation tool
# Amazon Profit Calculator

## 项目背景
用于计算FBA产品利润结构。

## 功能
- 成本输入
- 广告费计算
- 利润率输出

## 后续计划
增加自动化功能
# Amazon FBA Profit Calculator v1

def calculate_profit():
    product_price = float(input("Product Selling Price: "))
    product_cost = float(input("Product Cost: "))
    fba_fee = float(input("FBA Fee: "))
    ad_cost = float(input("Advertising Cost: "))

    total_cost = product_cost + fba_fee + ad_cost
    profit = product_price - total_cost
    profit_margin = (profit / product_price) * 100

    print("\n===== Result =====")
    print("Total Cost:", round(total_cost, 2))
    print("Profit:", round(profit, 2))
    print("Profit Margin:", round(profit_margin, 2), "%")


if __name__ == "__main__":
    calculate_profit()
