# Home Loan EMI Calculator

Single-file HTML calculator (no dependencies) based on the `Home_Loan_Calculator.xlsx` sheet.

## Inputs
- Loan amount, interest rate (% p.a.), tenure (years)
- First EMI date
- Rate basis: nominal with monthly compounding (bank standard) or effective annual rate (as in the original Excel)
- Bank rate change date and rate change (percentage points)

## Outputs
- EMI, total interest, total payable and loan end date
- EMIs paid before the rate change (auto-counted from the first EMI date)
- Outstanding balance at the rate change and the first EMI at the new rate
- Two options after a rate change:
  - **Fixed EMI** - EMI unchanged, tenure and end date change
  - **Fixed tenure** - tenure unchanged, EMI changes
- New end date, remaining interest, change vs original total, year-wise schedule

## Usage
Open `index.html` in any browser. Figures are indicative; bank statements may differ slightly.
