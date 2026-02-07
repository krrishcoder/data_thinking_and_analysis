
# AINextBill – Purchase Invoice Expense Analysis



The focus of this project is **data understanding, accounting logic, and clear insights**, rather than complex machine learning.

---

## Dataset

### Source

* **Synthetic dataset generated using Python**
* Designed to closely resemble real-world purchase invoice data
* Total records: **500**

### Fields

* `invoice_date`
* `vendor_name`
* `expense_category` (Raw Material, Office, Travel, Software, Utilities)
* `invoice_amount`
* `gst_rate`
* `gst_amount`

Dataset is generated inside the notebook to ensure reproducibility.

---

## Steps Followed

1. Generated realistic invoice data
2. Cleaned and prepared data using Pandas
3. Created derived features such as:

   * Month
   * Expense without GST
4. Analyzed monthly expense trends
5. Identified top spending categories
6. Detected unusually high expense months
7. Clustered vendors based on spending behavior

---

## Key Insights

* **Raw Material** contributes the highest to total expenses
* Expenses fluctuate monthly, indicating non-uniform purchasing behavior
* Certain months show abnormal spikes and should be reviewed
* Vendors can be grouped into strategic tiers using simple clustering

---

## Limitation

* Dataset is synthetic and may not capture all real-world accounting complexities
* No seasonal or business-event metadata was available

---

## Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib / Seaborn
* scikit-learn

---

## How to Run

1. Clone the repository
2. Open the notebook `AINextBill_Expense_Analysis.ipynb`
3. Run all cells

---

## Author

**Candidate: Data Science / ML Intern Applicant**

This project is intentionally kept **simple, readable, and business-oriented**, aligning with real accounting software use cases.

