# Income Tax Calculator for India 🇮🇳

A professional Python application to calculate income tax for both Old and New tax regimes in India for the Financial Year 2023-24.

## Features

- **Dual Regime Support**: Calculate taxes for both Old and New tax regimes
- **Progressive Tax Slabs**: Accurate calculation using proper tax slab methodology
- **Deduction Support**: Account for various deductions under the Old regime
- **Smart Recommendations**: Get instant advice on which regime saves you more money
- **User-Friendly**: Clean CLI interface with formatted currency display
- **Error Handling**: Robust input validation and error management

## Tax Slabs (FY 2023-24)

### Old Tax Regime
| Income Range | Tax Rate |
|--------------|----------|
| Up to ₹2.5 Lakhs | 0% |
| ₹2.5 - ₹5 Lakhs | 5% |
| ₹5 - ₹10 Lakhs | 20% |
| Above ₹10 Lakhs | 30% |

### New Tax Regime
| Income Range | Tax Rate |
|--------------|----------|
| Up to ₹2.5 Lakhs | 0% |
| ₹2.5 - ₹5 Lakhs | 5% |
| ₹5 - ₹7.5 Lakhs | 10% |
| ₹7.5 - ₹10 Lakhs | 15% |
| ₹10 - ₹12.5 Lakhs | 20% |
| ₹12.5 - ₹15 Lakhs | 25% |
| Above ₹15 Lakhs | 30% |

*Note: Education and Health Cess of 4% is applicable on the total tax amount in both regimes*

## Installation

### Prerequisites
- Python 3.6 or higher

### Clone the Repository
```bash
git clone https://github.com/yourusername/income-tax-calculator-india.git
cd income-tax-calculator-india
```

### Example Session
```
============================================================
INDIAN INCOME TAX CALCULATOR
Financial Year 2023-24
============================================================

Enter your annual salary (₹): 1200000

Deductions include: 80C, 80D, HRA, LTA, etc.
(Note: Deductions are only applicable in Old Regime)
Enter total deductions (₹): 50000

============================================================
INCOME TAX CALCULATION SUMMARY
============================================================

Gross Annual Salary: ₹1,200,000.00
Deductions Claimed: ₹50,000.00

------------------------------------------------------------
OLD TAX REGIME
------------------------------------------------------------
Taxable Income: ₹1,150,000.00
Income Tax: ₹162,500.00
Education & Health Cess (4%): ₹6,500.00
Total Tax Payable: ₹169,000.00
Take Home Salary: ₹1,031,000.00

------------------------------------------------------------
NEW TAX REGIME
------------------------------------------------------------
Taxable Income: ₹1,200,000.00
Income Tax: ₹150,000.00
Education & Health Cess (4%): ₹6,000.00
Total Tax Payable: ₹156,000.00
Take Home Salary: ₹1,044,000.00

============================================================
RECOMMENDATION
============================================================

✓ New Regime is better for you!
  You save: ₹13,000.00
============================================================
```

## Code Structure 📁

```
income-tax-calculator-india/
│
├── income_tax_calculator_app.ipynb    # Main application file
└── README.md                          # This file
```

## How It Works

1. **Input Collection**: The program collects your annual salary and deductions
2. **Tax Calculation**: 
   - For Old Regime: Taxable Income = Salary - Deductions
   - For New Regime: Taxable Income = Salary (no deductions allowed)
3. **Progressive Taxation**: Tax is calculated progressively across slabs
4. **Cess Addition**: 4% cess is added to the base tax amount
5. **Comparison**: Both regimes are compared to recommend the better option

## Deductions Supported (Old Regime) 

Common deductions that can be claimed:
- Section 80C (₹1.5 Lakhs limit)
- Section 80D (Medical Insurance)
- HRA (House Rent Allowance)
- LTA (Leave Travel Allowance)
- Standard Deduction (₹50,000)
- And more...

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Disclaimer

This calculator is for informational purposes only. Please consult a qualified tax professional for accurate tax planning and filing.

## Author

**Your Name**
- GitHub: [@ShreyasDasari](https://github.com/ShreyasDasari/)
- LinkedIn: [Shreyas Dasari](https://www.linkedin.com/in/shreyas-dasari/)


---

⭐ If you find this project helpful, please consider giving it a star!