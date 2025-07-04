
# 🚀 AI Bias Bounty Hackathon 2025 – Intersectional Fairness in Loan Approvals

**Crystal Tubbs / Metamorphic Curations**

---

## 🎯 Mission Statement

Modern financial systems risk amplifying historic inequalities when powered by biased AI. This project uncovers and mitigates algorithmic bias in loan approvals using industry-standard methods **and** state-of-the-art intersectional analysis. My goal: build more transparent, fair, and explainable machine learning models—because equitable access is non-negotiable.

---

## 🏆 Highlights

- **Deep Intersectional Audit:** Goes beyond one-variable bias, exposing *multi-dimensional disparities* (race × gender × disability, etc.)
- **Mitigation in Action:** Not just diagnosing, but actively reducing unfairness with cutting-edge algorithms (Fairlearn, AIF360, etc.)
- **Explainability-First:** SHAP and LIME insights reveal *why* the model acts as it does
- **Polished Visuals:** Heatmaps and plots spotlight where bias lurks—and how it shrinks after intervention
- **Reproducibility:** One-click pipeline, ready to run, retrain, and deploy

---

## 📊 Key Results

- **Accuracy (Test Set):** [PLACEHOLDER]
- **AUC:** [PLACEHOLDER]
- **Fairness Metrics (Before/After):**

  | Metric                 | Baseline | Mitigated |
  |------------------------|----------|-----------|
  | Statistical Parity     | [x.xx]   | [x.xx]    |
  | Disparate Impact       | [x.xx]   | [x.xx]    |
  | Equal Opp. Difference  | [x.xx]   | [x.xx]    |
  | Average Odds Diff.     | [x.xx]   | [x.xx]    |
  | Theil Index            | [x.xx]   | [x.xx]    |

- **Most Improved Group:** 
- **Remaining Challenge:** 

---

## 🔬 Methodology

### 1. **Data Pipeline**
- **Imputation:** KNNImputer for missing values
- **Encoding:** One-hot and binary for categorical/sensitive attributes
- **Scaling:** StandardScaler (fit on train, applied to test)
- **Feature Selection:** SHAP (top 20 features for best performance + interpretability)

### 2. **Model Training**
- Benchmarked Logistic Regression, Random Forest, XGBoost, and simple Neural Network
- Chose [PLACEHOLDER]  for best fairness–accuracy tradeoff

### 3. **Bias Detection & Mitigation**
- **Fairness Metrics:** Calculated with AIF360 & Fairlearn (SPD, DI, EOD, AOD, FNR)
- **Mitigation:** ExponentiatedGradient, sample reweighting, [and/or other method]
- **Intersectional Auditing:** Approval rates/metrics for every major demographic intersection

### 4. **Interpretability**
- **SHAP:** Global and local feature importance plots
- **LIME:** Local explanations on challenging samples

---

## 📈 Results & Visualizations

- Approval rates by group and intersection:  
  ![PLACEHOLDER]
- Fairness metrics table (before/after mitigation)
- SHAP summary plot for top features
- LIME explanation screenshot 

See `/outputs/` and `/images/` for all graphics and results.

---

## 🛠️ How to Reproduce

```bash
git clone https://github.com/[YOUR_USERNAME]/ai-bias-bounty-2025.git
cd ai-bias-bounty-2025

# Set up your environment
python -m venv venv
source venv/bin/activate        # (or venv\Scripts\activate on Windows)
pip install -r requirements.txt

# Run the pipeline
python loan_model.py            # Or: jupyter notebook loan_model.ipynb

# Generate submission
python generate_submission.py   # Outputs submission.csv
 ```
---

## 🌍 Real-World Impact

If deployed as-is, the baseline model would have systematically denied fair access to **[PLACEHOLDER]** by **[PLACEHOLDER]%**.  
My mitigation strategies reduced the largest observed disparities by **[PLACEHOLDER]**, while maintaining strong predictive accuracy.

**Key insight:**

> _Intersectional bias compounds disadvantage. My approach demonstrates real progress toward algorithmic justice in high-stakes financial decisions._

---

## 📝 Limitations & Future Work

- **Data Gaps:** [PLACEHOLDER]
- **Model Limitations:** [PLACEHOLDER]
- **Next Steps:** Adversarial debiasing, threshold optimization, model monitoring in production

---

## 🎥 Demo

[PLACEHOLDER]

---

## 🤝 Contact & Credits

**Author:** Crystal Tubbs (`msmetamorphosis` on GitHub)  
Metamorphic Curations

**Inspired by:**
- AI Fairness 360 (IBM Research)
- Fairlearn (Microsoft)
- Bellamy et al., 2018

---

## 📄 License

This project is released under the MIT License.

---

_Ready to make AI lending fair—one intersection at a time._
