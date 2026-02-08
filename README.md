# 🏠 PropertyPlan SG

A comprehensive web-based property purchase calculator designed specifically for Singapore's real estate market. Plan your HDB or Condo purchase with detailed financial breakdowns, stamp duty calculations, and mortgage payment tracking.

![PropertyPlan SG Screenshot](screenshot.png)

## 🌟 Features

### Property Types
- **HDB Flat (Resale)** - With HDB loan support and specific LTV rules
- **Private Condo (Resale)** - Bank loan options with tiered LTV limits

### Financial Calculations
- ✅ **Buyer's Stamp Duty (BSD)** - Progressive tier calculation
- ✅ **Additional Buyer's Stamp Duty (ABSD)** - Based on buyer profile (SC/PR/Foreigner)
- ✅ **Loan-to-Value (LTV)** Validation - Enforces MAS regulations
- ✅ **TDSR Calculation** - Total Debt Servicing Ratio monitoring
- ✅ **CPF Usage** - Track CPF allocation for down payment and monthly payments

### User Profile Management
- Age-based loan tenure validation (max 30 years or until age 65)
- Monthly household income tracking
- CPF available for down payment
- Buyer profile selection (affects ABSD rates)

### Loan Features
- **HDB Loan** - Fixed rate (CPF OA + 0.1%)
- **Bank Loans** - Fixed or floating rates (SORA-based)
- Flexible loan tenure (1-30 years with age validation)
- Real-time interest rate updates

### Visualizations & Reports
- 📊 **Payment Breakdown Chart** - Principal vs Interest over time
- 📅 **Monthly Payment Schedule** - Detailed amortization table
- 💾 **CSV Export** - Download complete payment schedule
- 📈 **Progress Tracking** - Visual down payment progress bar

## 🎯 Key Highlights

### Singapore-Specific Regulations
- **LTV Limits**: 75% for first $1M, 45% for amounts above
- **HDB Rules**: 80% LTV for HDB with lower down payment requirements
- **ABSD Rates**: 
  - 0% - SC 1st property
  - 20% - SC 2nd property
  - 30% - SC 3rd+ property
  - 5% - PR 1st property
  - 30% - PR 2nd+ property
  - 60% - Foreigners
  - 35-65% - Entities

### Smart Validations
- Minimum down payment enforcement (20% HDB, 25% Condo)
- Maximum loan tenure based on age
- Real-time TDSR warnings (55% limit)
- Automatic thousand separators for all currency fields

## 🚀 Live Demo

[View Live Demo](https://yourusername.github.io/propertyplan-sg)

## 💻 Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with gradients and transitions
- **Vanilla JavaScript** - No dependencies required
- **Chart.js** - Interactive data visualizations
- **Responsive Design** - Works on desktop, tablet, and mobile

## 📸 Screenshots

### User Profile Section
![User Profile](screenshots/user-profile.png)

### Purchase Details
![Purchase Details](screenshots/purchase-details.png)

### Financial Summary
![Financial Summary](screenshots/financial-summary.png)

### Payment Schedule
![Payment Schedule](screenshots/payment-schedule.png)

## 🛠️ Installation & Usage

### Option 1: Direct Use
1. Download `PropertyPlan_SG.html`
2. Open in any modern web browser
3. No installation required!

### Option 2: Local Server
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx http-server

# Then visit http://localhost:8000
```

### Option 3: Deploy to GitHub Pages
1. Fork this repository
2. Go to Settings → Pages
3. Select branch and deploy
4. Access at `https://yourusername.github.io/propertyplan-sg`

## 📖 How to Use

1. **Enter Your Profile**
   - Input your age, income, and CPF available
   - Select your buyer profile (SC/PR/Foreigner)

2. **Configure Property Details**
   - Choose property type (HDB or Condo)
   - Enter property price
   - Adjust down payment percentage
   - Set loan tenure and interest rate

3. **Review Financial Summary**
   - Check total cash needed
   - Review ABSD and BSD amounts
   - Verify TDSR ratio is within limits

4. **Analyze Payment Schedule**
   - View payment breakdown chart
   - Examine monthly payment schedule
   - Export to CSV for detailed analysis

## 🧮 Calculation Formulas

### Monthly Mortgage Payment
```
M = P × [r(1 + r)^n] / [(1 + r)^n - 1]

Where:
M = Monthly payment
P = Principal loan amount
r = Monthly interest rate
n = Total number of payments
```

### Buyer's Stamp Duty (BSD)
```
First $180,000: 1%
Next $180,000: 2%
Next $640,000: 3%
Above $1,000,000: 4%
```

### TDSR (Total Debt Servicing Ratio)
```
TDSR = (Monthly Debt Obligations / Gross Monthly Income) × 100%
Limit: 55%
```

## 🎨 Features in Detail

### Dynamic Property Type Switching
- Automatically adjusts LTV limits
- Updates available loan types
- Recalculates ABSD based on property type
- Changes down payment requirements

### Real-Time Validation
- Down payment warnings if below minimum
- Loan tenure caps based on age
- Visual indicators for invalid inputs
- Helpful tooltips and remarks

### Export Functionality
- Generate complete payment schedule
- CSV format compatible with Excel/Google Sheets
- Includes all months from start to end
- Ready for financial planning tools

## 🔮 Future Enhancements

- [ ] Multi-language support (English, Chinese, Malay, Tamil)
- [ ] Save/load scenarios feature
- [ ] Comparison mode (compare multiple properties)
- [ ] Rental yield calculator
- [ ] Property appreciation projections
- [ ] Integration with actual property listings
- [ ] Mobile app version
- [ ] Dark mode toggle

## 📜 License

MIT License - Feel free to use this project for personal or commercial purposes.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📧 Contact

Vasant98 - [LinkedIn](https://www.linkedin.com/in/vasanttan/)

Project Link: [https://github.com/Vasant98/propertyplan-sg](https://github.com/Vasant98/propertyplan-sg)

## 🙏 Acknowledgments

- Singapore's Monetary Authority (MAS) for regulatory guidelines
- HDB and IRAS for stamp duty information
- Chart.js for data visualization
- Singapore property market resources

## ⚖️ Disclaimer

This calculator is for educational and planning purposes only. Always consult with licensed financial advisors, property agents, and lawyers before making property purchase decisions. Regulations and rates may change - verify current rules with official sources.

---

Made with ❤️ for Singapore property buyers
