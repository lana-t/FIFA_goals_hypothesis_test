# ⚽ Do Women’s FIFA World Cup Matches Have More Goals Than Men’s?

This project investigates whether women’s FIFA World Cup matches (2002–present) feature more goals per game than men’s.  
Using official match results datasets, I cleaned and filtered the data, visualised goal distributions, and applied a statistical hypothesis test to answer the question.

---

## 📂 Project Structure
- `FIFA.ipynb` — Jupyter Notebook with full analysis  
- `women_results.csv` — dataset of international women’s football results  
- `men_results.csv` — dataset of international men’s football results  

---

## 🔍 Research Question
Are more goals scored in women’s international soccer matches than in men’s?  

- **Null hypothesis (H₀):** The mean number of goals per match is the same.  
- **Alternative hypothesis (H₁):** The mean number of goals per match is greater in women’s matches.  
- **Significance level (α):** 0.10  

---

## 📊 Methods
1. **Data preparation**: Filtered FIFA World Cup matches (2002–present, excluding qualifiers).  
2. **Exploratory analysis**: Visualised goals per match distributions.  
3. **Hypothesis testing**: Used the **Mann–Whitney U test** (non-parametric, since data was not normally distributed).  

---

## ✅ Results
- **p-value:** 0.005  
- **Decision:** Reject H₀ at α = 0.10  
- **Conclusion:** Women’s FIFA World Cup matches tend to feature more goals per match than men’s.  

---

## 🛠️ Requirements
To run the notebook, install the following Python libraries:
```bash
pip install pandas matplotlib pingouin
