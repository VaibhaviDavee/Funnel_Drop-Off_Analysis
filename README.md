 
# Funnel Drop-Off Analysis - E-commerce Conversion Optimization  

**Python | Pandas | Matplotlib | Seaborn | SciPy**

---

## 📌 Overview  
This project analyzes user behavior across an e-commerce funnel to identify where users drop off and how it impacts overall conversion.

Out of **5,000 users**, only **1,010 completed a purchase**, resulting in a **20.2% conversion rate**.  
The goal is to pinpoint the exact stage where users drop and understand the underlying reason using data and statistical testing.

---

## 🚨 Key Insight  
The most critical drop (**~60%**) occurs at:  
👉 **Product Page → Cart**

Users are actively spending time on product pages but are not adding items to the cart.  
This indicates a **conversion problem at the product page**, not an issue with traffic or checkout.

---

## 📊 Analysis Performed  
- Funnel stage drop-off analysis  
- Conversion rate calculation  
- Device-wise comparison  
- Referral source analysis  
- Time-based behavior trends  
- Product page engagement analysis  
- Statistical testing using Chi-square  

---

## 🧪 Key Findings  
- Device type → ❌ No significant impact (p = 0.98)  
- Referral source → ❌ No significant difference (p = 0.47)  
- Time of visit → ❌ No clear pattern  
- Engagement time → ⚠️ Same for buyers & non-buyers  

👉 **Conclusion:**  
The issue is not *who* is coming or *when* they visit —  
it is **how effectively the product page converts interest into action**.

---

## 💡 Business Impact  
- ~2,388 users drop at the product page stage  
- Recovering just **10%** of these users  
→ can generate **~$11,900 additional revenue per 5,000 sessions**  

This makes the **Product Page → Cart transition the highest impact optimization point**.

---

## ⚠️ Challenges Faced  
- Tracking **user journey across funnel steps** accurately  
- Ensuring **data consistency and correct session mapping**  
- Applying and interpreting **statistical tests (Chi-square)** correctly  
- Avoiding misleading conclusions from visual patterns  
- Identifying limitations due to **synthetic dataset (uniform behavior across segments)**  

---

## 🛠️ Tech Stack  
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- SciPy (Statistical Testing)  
- Jupyter Notebook  

---

## ▶️ How to Run  

```bash
git clone https://github.com/VaibhaviDavee/funnel-drop-analysis.git
cd funnel-drop-analysis
pip install -r requirements.txt
jupyter notebook
```

## 💡 Conclusion  

This analysis highlights that conversion is not limited by traffic volume, device type, or checkout efficiency.  

The real bottleneck lies at a single, high-impact stage — the **Product Page → Cart transition**, where user intent fails to convert into action.  

Despite users actively engaging with product pages, the lack of persuasive design, clarity, or trust signals leads to significant drop-offs.  

👉 This makes the product page the most critical optimization point in the entire funnel.  

Even small improvements at this stage can drive **disproportionately high revenue gains**, making it the most valuable area for business focus.  

In short, the problem is not attracting users —  
it is **converting interested users into buyers**.
