# 🛒 Market Basket Analysis with Apriori Algorithm

This project applies **association rule mining** using the **Apriori algorithm** to uncover frequent itemsets and buying patterns in supermarket transactions. It includes analysis of a toy dataset and a real-world checkpoint dataset.

---

## 📦 Datasets

- **Toy Dataset**: A small, hardcoded list of customer baskets for demonstration.
- **Checkpoint Dataset**: A real-world transaction log from a supermarket, where each row represents a customer's basket.

---

## 🔍 Objectives

1. **Run Apriori on Toy Dataset**  
   - Identify frequent itemsets and strong association rules.
   - Interpret results to understand basic co-purchase behavior.

2. **Explore Checkpoint Dataset with Pandas & Plotly**  
   - Visualize item frequencies and co-occurrence patterns.
   - Identify top-selling items and frequently bought-together pairs.

3. **Run Apriori on Checkpoint Dataset**  
   - Extract high-confidence rules to guide business decisions.
   - Suggest actionable strategies for inventory, promotions, and layout optimization.

---

## 📊 Key Findings

- **Popular Items**: Items like `Pants`, `Scarf`, and `mineral water` appear frequently across baskets.
- **Strong Associations**: Rules such as `{Skirt} → {Sneakers}` and `{chocolate} → {mineral water}` indicate strong co-purchase behavior.
- **Business Strategy**:
  - **Cross-Promotions**: Bundle frequently paired items to boost sales.
  - **Store Layout**: Place associated items near each other to encourage impulse buys.
  - **Inventory Planning**: Prioritize stock for high-frequency and high-confidence items.

---

## 🧠 Tools Used

- **Python**
- **Pandas** for data manipulation
- **Plotly** for interactive visualizations
- **mlxtend** for Apriori algorithm and association rule mining

---

## 🚀 How to Run

1. Load the dataset using `read_csv_as_list_of_lists()`.
2. Preprocess baskets and flatten items.
3. Visualize item frequencies and pairs with Plotly.
4. Apply Apriori using `mlxtend.frequent_patterns`.
5. Interpret rules and generate business recommendations.

---

## 📈 Business Impact

By understanding customer purchasing habits, supermarkets can:
- Increase revenue through targeted promotions.
- Improve customer experience with smarter product placement.
- Reduce waste by optimizing inventory based on demand patterns.

---

