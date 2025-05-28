# PPS Alert - Insurance Summary Generator

A simple web tool to quickly generate formatted insurance summaries for patient records.

## 🌐 Access the Tool
**Live URL:** https://phoenixglass.github.io/index/

## 📋 How to Use

### Quick Start
1. **Choose your rates**: Click CT, NY, NJ, or Self-Pay buttons to auto-fill service rates
2. **Fill in patient info**: Enter deductible/OOP amounts, coinsurance, etc.
3. **Click "Generate Output"** to create your summary
4. **Click "Copy Output"** to copy to clipboard and paste into patient records

### Key Features

**🏥 Service Rates**
- Click rate buttons (CT/NY/NJ/Self-Pay) to auto-fill all service prices
- Check "In Network" if applicable

**💰 Deductible & OOP**
- Enter amounts like: "2000 out of 6000" 
- Choose "Combined" or "Separate" status
- Add "as of" date (e.g., "4/10")

**📊 Post-Deductible Calculator**
- Enter percentage (e.g., "40") and click "Post-Deductible"
- Automatically calculates patient responsibility
- Rounds up for out-of-network rates

**🏥 PIF (Paid In Full)**
- Click "PIF" button and select year
- When PIF is active, service rates AND deductible/OOP info are hidden (since everything is paid in full)
- PIF appears first in output: "In Network: 2025 PIF | ..."

**📞 Other Options**
- **PIF**: Select year from dropdown
- **Telemed**: Choose Yes/No/Self-Pay
- **Coinsurance**: Enter percentage
- **Insurance Renews**: Enter date

## 📝 Sample Output

**Standard Output:**
```
In Network: Assessment $118.19 | IOP $298.00 | $2,000/$6,000 deductible used as of 4/10 | 40% coinsurance | Ins Renews 1/2026 | Telemed: Yes
```

**PIF (Paid In Full) Output:**
```
In Network: 2025 PIF | Ins Renews 1/2026 | Telemed: Yes
```

## 🚀 Tips
- **Press Enter** anywhere to generate output
- **Click "Clear All"** to reset the entire form
- The output is automatically formatted with proper dollar signs and commas
- Copy and paste directly into your patient management system

## 🔧 Need Help?
If you encounter any issues, contact the tool creator or check that you're using the latest version at the URL above.
