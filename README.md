# mortgage-calculator-

🏡 Mortgage Repayments Calculator

An interactive Streamlit web app that helps you calculate monthly mortgage repayments, total interest, and visualize your loan balance over time.

This tool allows users to input key parameters — such as home value, deposit, interest rate, and loan term — and instantly see how their repayment plan shapes up across years.

⸻

🚀 Features

✅ Dynamic Input Fields — Instantly update calculations as you tweak values
✅ Monthly Repayment Breakdown — See how much you’ll pay each month
✅ Total Repayments & Interest — Understand the lifetime cost of your loan
✅ Interactive Chart — Visualize the declining balance year-by-year
✅ Clean UI — Built with Streamlit’s responsive and modern layout

⸻

🧮 How It Works
	1.	Input Parameters:
	•	🏠 Home Value
	•	💰 Deposit Amount
	•	💸 Interest Rate (Annual %)
	•	⏳ Loan Term (Years)
	2.	Automatic Calculations:
	•	Loan Amount = Home Value - Deposit
	•	Monthly Payment = Based on standard amortization formula
	•	Total Interest = Total Repayments - Principal
	3.	Visual Output:
	•	Key metrics displayed in elegant Streamlit metrics cards
	•	Interactive line chart showing your remaining balance each year

⸻

📊 Formula Used

\text{Monthly Payment} = P \times \frac{r(1+r)^n}{(1+r)^n - 1}

Where:
	•	P = Loan Amount
	•	r = Monthly Interest Rate (Annual Rate / 12)
	•	n = Number of Payments (Loan Term × 12)

⸻

🖥️ Preview

📸 Example Output:
	•	Monthly Repayment: $2,271.16
	•	Total Repayment: $817,618
	•	Total Interest: $417,618
	•	A sleek line chart tracking your decreasing loan balance year over year.

⸻

⚙️ Installation & Usage

1️⃣ Clone the repository

git clone https://github.com/your-username/mortgage-repayment-calculator.git
cd mortgage-repayment-calculator

2️⃣ Install dependencies

pip install streamlit pandas matplotlib

3️⃣ Run the Streamlit app

streamlit run app.py

Then open the displayed local URL (usually http://localhost:8501) in your browser.

⸻

🧠 Tech Stack
	•	Frontend & Logic: Streamlit￼
	•	Data Handling: Pandas￼
	•	Visualization: Matplotlib￼ / Streamlit charts
	•	Language: Python 3.9+

⸻

🌟 Future Enhancements

✨ Add extra repayment & prepayment options
📉 Include amortization heatmaps
📆 Export repayment schedules as Excel or PDF
🌍 Add currency and regional formatting options

⸻

💡 Example Use Case

Perfect for:
	•	Home buyers exploring loan options
	•	Financial advisors simulating interest rate impacts
	•	Students learning financial modeling & amortization
