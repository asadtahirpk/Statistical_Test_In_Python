# Statistical Tests in Python

This repository contains comprehensive hands-on practice of **parametric** and **non-parametric statistical tests** implemented in Python. The goal is to strengthen statistical foundations essential for Data Science and Machine Learning applications.

## 📌 Topics Covered

### Parametric Tests
- **Independent T-Test** - Compare means between two independent groups
- **Paired T-Test** - Compare means from the same subjects at different times
- **One-Way ANOVA** - Compare means across multiple groups
- **Two-Way ANOVA** - Analyze the effect of two factors simultaneously
- **Pearson Correlation** - Measure linear correlation between variables
- **Simple Linear Regression** - Model relationship between two variables
- **Multiple Linear Regression** - Model relationship with multiple predictors

### Non-Parametric Tests
- **Chi-Square Test** - Goodness of Fit & Test of Independence
- **Mann–Whitney U Test** - Non-parametric alternative to independent t-test
- **Wilcoxon Signed-Rank Test** - Non-parametric alternative to paired t-test
- **Kruskal–Wallis Test** - Non-parametric alternative to one-way ANOVA
- **Friedman Test** - Non-parametric alternative to repeated measures ANOVA
- **Spearman Rank Correlation** - Non-parametric correlation measure

## ⚙️ Requirements

- **Python 3.8+**
- **Core Libraries:**
  - `numpy` - Numerical computations
  - `pandas` - Data manipulation and analysis
  - `scipy` - Statistical functions
  - `statsmodels` - Statistical modeling
- **Visualization:**
  - `matplotlib` - Basic plotting
  - `seaborn` - Statistical data visualization

### Installation

Install all dependencies using pip:

```bash
pip install numpy pandas scipy statsmodels matplotlib seaborn
```

Or using conda:

```bash
conda install numpy pandas scipy statsmodels matplotlib seaborn
```

## 🚀 How to Run

1. **Clone this repository**
   ```bash
   git clone https://github.com/asadtahirpk/Statistical_Test_In_Python.git
   cd Statistical_Test_In_Python
   ```

2. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook Statistical_Test_In_Python.ipynb
   ```

3. **Alternative: Run with JupyterLab**
   ```bash
   jupyter lab Statistical_Test_In_Python.ipynb
   ```

## 📂 Project Structure

```
Statistical_Tests/
├── Statistical_Test_In_Python.ipynb    # Main Jupyter Notebook with all implementations
├── README.md                # Project Documentation
├── requirements.txt         # Package dependencies                  
    └── ...
```

## 🧠 Key Concepts Covered

### When to Use Parametric vs Non-Parametric Tests

| **Parametric Tests** | **Non-Parametric Tests** |
|---------------------|---------------------------|
| Assume normal distribution | No distribution assumptions |
| Use actual data values | Use ranks or categories |
| More powerful when assumptions met | More robust to outliers |
| Examples: t-test, ANOVA | Examples: Mann-Whitney, Kruskal-Wallis |

### Statistical Test Selection Guide

- **Comparing 2 groups:** Independent t-test (parametric) vs Mann-Whitney U (non-parametric)
- **Comparing paired data:** Paired t-test vs Wilcoxon signed-rank test
- **Comparing 3+ groups:** ANOVA vs Kruskal-Wallis test
- **Association between variables:** Pearson correlation vs Spearman correlation
- **Categorical relationships:** Chi-square test of independence

## 📊 Sample Use Cases

Each test includes practical examples with:
- **Problem statement** and research questions
- **Assumption checking** (normality, homogeneity of variance)
- **Step-by-step implementation** in Python
- **Results interpretation** and conclusions
- **Visualization** of findings

## ✨ Learning Outcomes

After completing this project, you will have:

- ✅ **Understood** the fundamental difference between parametric & non-parametric tests
- ✅ **Mastered** hypothesis testing methodology and interpretation
- ✅ **Gained** hands-on experience in Python statistical analysis
- ✅ **Developed** skills in choosing appropriate statistical tests
- ✅ **Practiced** real-world data analysis scenarios

**Total Learning Time:** 3–4 days of consistent learning & practice

## 🔗 Additional Resources

- [SciPy Statistical Functions Documentation](https://docs.scipy.org/doc/scipy/reference/stats.html)
- [Statsmodels User Guide](https://www.statsmodels.org/stable/user-guide.html)
- [Python for Data Analysis by Wes McKinney](https://wesmckinney.com/book/)

## 🤝 Contributing

Feel free to contribute by:
- Adding new statistical tests
- Improving existing implementations
- Adding more real-world examples
- Enhancing documentation

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Happy Learning!** 🎓📊

*If you found this repository helpful, please give it a ⭐ star!*
