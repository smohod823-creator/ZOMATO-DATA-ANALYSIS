# 🍽️ Zomato Data Analysis

An Exploratory Data Analysis (EDA) project on a Zomato restaurant dataset to uncover trends and insights about restaurant types, customer votes, ratings, spending habits, and ordering modes.

---

## 📌 Project Overview

This project performs exploratory data analysis on a Zomato dataset containing 148 restaurant records. It explores patterns in restaurant types, customer behavior, and ratings to help understand the food delivery landscape.

---

## 📊 Key Questions Explored

1. **What types of restaurants are most common?**
2. **Which restaurant type receives the maximum votes?**
3. **What is the distribution of restaurant ratings?**
4. **What is the average spending by couples?**
5. **Which ordering mode (online vs offline) receives higher ratings?**
6. **What is the relationship between restaurant type and online ordering?**

---

## 🔍 Key Findings

- **Dining** restaurants make up the majority of the dataset.
- **Dining** restaurants have received the maximum total votes from customers.
- Most restaurants have ratings between **3.5 and 4** out of 5.
- The majority of couples prefer restaurants with an approximate cost of **₹300**.
- **Online orders** tend to receive higher ratings compared to offline orders.
- A heatmap reveals how different restaurant types correlate with the availability of online ordering.

---

## 🗂️ Dataset

The dataset (`Zomato data .csv`) contains the following columns:

| Column | Description |
|---|---|
| `name` | Name of the restaurant |
| `online_order` | Whether the restaurant accepts online orders (Yes/No) |
| `book_table` | Whether table booking is available (Yes/No) |
| `rate` | Customer rating (e.g., 4.1/5) |
| `votes` | Number of votes received |
| `approx_cost(for two people)` | Approximate cost for two people (in INR) |
| `listed_in(type)` | Category/type of the restaurant (e.g., Buffet, Dining, Cafes) |

> **Dataset size:** 148 rows × 7 columns

---

## 🛠️ Tech Stack

- **Python 3**
- **Pandas** — Data manipulation and analysis
- **NumPy** — Numerical operations
- **Matplotlib** — Static visualizations
- **Seaborn** — Statistical data visualization
- **Google Colab** — Development environment

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/zomato-data-analysis.git
cd zomato-data-analysis
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Add the dataset

Place your `Zomato data .csv` file in the project root directory (or update the file path in the notebook).

### 4. Run the notebook

Open `Zomato_Data_Analysis.ipynb` in Jupyter Notebook, JupyterLab, or Google Colab and run all cells.

---

## 📁 Project Structure

```
zomato-data-analysis/
│
├── Zomato_Data_Analysis.ipynb   # Main analysis notebook
├── Zomato data .csv             # Dataset (add manually)
├── requirements.txt             # Python dependencies
└── README.md                    # Project documentation
```

---

## 📈 Visualizations Included

- Count plot — Distribution of restaurant types
- Line chart — Total votes by restaurant type
- Histogram — Distribution of restaurant ratings
- Count plot — Approximate cost for two people
- Box plot — Rating comparison between online and offline orders
- Heatmap — Restaurant type vs. online order availability

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
