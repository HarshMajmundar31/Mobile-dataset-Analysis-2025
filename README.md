# 📱 Mobile Dataset Analysis 2025

**Exploratory Data Analysis (EDA) of the 2025 mid-range smartphone market (₹20,000–₹30,000) using Python, Pandas, and Matplotlib to evaluate price-to-performance trends.**
---
## 📌 Project Overview
With hundreds of smartphones competing in the ₹20k–₹30k price bracket, choosing the best value-for-money device is increasingly difficult. This project performs a comprehensive **Exploratory Data Analysis (EDA)** on mid-range smartphones available in India in 2025, helping consumers and analysts understand which brands and specs offer the best performance per rupee.

---
## 🎯 Objectives
- Analyze and compare smartphones in the ₹20,000–₹30,000 price range
- Identify key hardware and software features that influence pricing
- Discover price-to-performance trends across brands
- Visualize distribution of specs like RAM, storage, battery, camera, and processor
- Help buyers make data-driven purchase decisions
---
## 🗂️ Repository Structure
Mobile-dataset-Analysis-2025/
│
├── Mobile_dataset_analysis.ipynb   # Main Jupyter Notebook with full EDA
├── README.md                        # Project documentation
├── .gitignore                       # Files excluded from version control
└── LICENSE                          # MIT License
## 🔍 Analysis Highlights

The notebook covers the following analytical steps:

1. **Data Loading & Inspection** — Loading the dataset, checking shape, data types, and null values
2. **Data Cleaning** — Handling missing values, fixing data types, removing duplicates
3. **Univariate Analysis** — Distribution of price, RAM, storage, battery capacity, camera specs
4. **Bivariate Analysis** — Price vs. RAM, price vs. processor tier, price vs. display resolution
5. **Brand-wise Comparison** — Which brands dominate the ₹20k–₹30k segment
6. **Feature Correlation** — Heatmaps to understand which specs are most correlated with price
7. **Price-to-Performance Scoring** — Identifying top value-for-money smartphones

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| **Python 3.x** | Core programming language |
| **Pandas** | Data manipulation and analysis |
| **Matplotlib** | Data visualization |
| **Seaborn** | Statistical visualizations |
| **Jupyter Notebook** | Interactive development environment |
| **NumPy** | Numerical computations |

## 📊 Key Features Analyzed

- **Price** (₹20,000 – ₹30,000 range)
- **RAM** (4GB / 6GB / 8GB / 12GB)
- **Internal Storage** (64GB / 128GB / 256GB)
- **Battery Capacity** (mAh)
- **Charging Speed** (W)
- **Rear Camera** (MP)
- **Front Camera** (MP)
- **Display** (Size, Resolution, Refresh Rate)
- **Processor** (Brand and tier)
- **Operating System / Android version**
- **Brand**

## 🚀 Getting Started

### Prerequisites
Make sure you have Python 3.x installed along with the following libraries:
**pip install pandas matplotlib seaborn numpy jupyter**

### Running the Notebook

1. **Clone the repository:**
   
   git clone https://github.com/HarshMajmundar31/Mobile-dataset-Analysis-2025.git
   cd Mobile-dataset-Analysis-2025
  

2. **Launch Jupyter Notebook:**
   
   jupyter notebook
   

3. **Open the notebook:**
   Navigate to `Mobile_dataset_analysis.ipynb` and run all cells.

## 📈 Sample Insights

- 🔋 Most phones in this range offer **5000 mAh** battery or higher
- 📸 Camera megapixels alone don't justify higher pricing — processor tier matters more
- 🏆 Certain brands consistently offer better specs per rupee than others
- 💾 128GB storage has become the baseline for this price segment in 2025
- ⚡ Fast charging (67W+) is increasingly available even below ₹25,000

## 📁 Dataset

The dataset was curated from publicly available smartphone specification listings and e-commerce platforms for mid-range devices available in India in 2025.

**Note:** The dataset CSV is not included in this repository. To replicate the analysis, you can collect data from sources like [GSMArena](https://www.gsmarena.com/), [Flipkart](https://www.flipkart.com/), or [Amazon India](https://www.amazon.in/).

## 🤝 Contributing

Contributions, suggestions, and feedback are welcome!

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Harsh Majmundar**

- GitHub: [@HarshMajmundar31](https://github.com/HarshMajmundar31)


## ⭐ Show Your Support

If you found this project helpful, please consider giving it a ⭐ on GitHub — it helps others discover it too!



*Made with ❤️ and Python*
