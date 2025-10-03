# Investment Analysis Calculator

A comprehensive web-based calculator that helps investors evaluate whether an investment opportunity makes financial sense based on their goals, available capital, and expected returns.

![Investment Calculator](https://img.shields.io/badge/version-1.0-blue) ![License](https://img.shields.io/badge/license-MIT-green)

## 🎯 Features

- **Goals & Capital Planning**: Track your financial goals and available investment capital

- **Investment Details**: Input purchase price, loan terms, and all associated costs
- **Real-time Calculations**: Automatic monthly payment calculations and cash flow analysis
- **Visual Decision Making**: Clear, color-coded indicators showing if an investment meets your criteria
- **Return Metrics**: Calculate cash-on-cash return and annual net income
- **Mobile Responsive**: Works perfectly on desktop, tablet, and mobile devices

## 📊 What It Calculates

### Financial Metrics
- Total capital available (cash + liquid assets)
- Monthly loan payments using standard amortization formula
- Total monthly expenses (loan, operations, taxes, insurance, etc.)
- Net monthly income
- Breakeven analysis
- Cash-on-cash return percentage
- Annual net income projections

### Decision Factors
- Whether you have sufficient capital for the investment
- If the investment meets your desired monthly income goals
- Overall investment viability score

## 🚀 Quick Start

### Option 1: Direct Use
Simply open the `index.html` file in any modern web browser. No installation or server required!

### Option 2: Host on GitHub Pages
1. Fork this repository
2. Go to Settings → Pages
3. Select your branch (usually `main`)
4. Your calculator will be live at: `https://yourusername.github.io/investment-calculator`

### Option 3: Use on Your Website
Copy the HTML file and upload it to your web hosting, or embed it in your existing site.

## 📁 File Structure

## 💻 Usage

### Step 1: Goals & Capital Tab
1. Enter your current monthly budget
2. Input your desired monthly income from the investment
3. Add your available cash
4. Include other liquid assets
5. View your total capital available

### Step 2: Investment Details Tab
1. **Purchase Details**
   - Total purchase price
   - Down payment amount

2. **Loan Details**
   - Loan amount (auto-calculated or manual entry)
   - Interest rate (%)
   - Loan term in years

3. **Monthly Expenses**
   - Operational expenses
   - Commissions and fees
   - Property taxes
   - Insurance
   - Other monthly costs

4. **Expected Income**
   - Promised monthly income from the investment

### Step 3: Analysis & Decision Tab
Review your complete investment analysis including:
- Financial summary
- Monthly cash flow breakdown
- Income requirements
- Return metrics
- Decision factors with visual indicators

## 🎨 Customization

### Branding
To add your own branding, edit the header section in `index.html`:
```html
<div class="bg-gradient-to-r from-blue-600 to-blue-700 text-white p-6">
    <!-- Add your logo here -->
    <h1 class="text-2xl font-bold">Your Brand - Investment Calculator</h1>
<div class="mt-6 text-center text-sm text-gray-600">
    <p>Your Company Name - yourwebsite.com</p>
</div>
</div>

M = P × [r(1 + r)^n] / [(1 + r)^n - 1]

Where:
M = Monthly payment
P = Principal loan amount
r = Monthly interest rate (annual rate / 12)
n = Number of payments (years × 12)

CoC Return = (Annual Net Income / Total Cash Invested) × 100

Where:
Annual Net Income = Monthly Net Income × 12
Total Cash Invested = Down Payment + Fees