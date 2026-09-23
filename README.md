# 🇳🇵 Nepali Interest Calculator (BS)

A clean, modern, and fully responsive web application to calculate interest based on **Nepali Dates (Bikram Sambat)**. 

This tool uses the **App Anniversary Method** (Carry-Forward Principal), where the closing balance of a period becomes the opening principal for the next period.

🔗 **Live Demo:** [https://your-username.github.io/nepali-interest-calculator/](https://your-username.github.io/nepali-interest-calculator/)
*(Replace `your-username` with your actual GitHub username)*

## ✨ Features
- **📱 Mobile-First Responsive Design:** On mobile, the data table automatically transforms into beautiful, easy-to-read vertical cards. On desktop, it remains a clean, wide table.
- **🌙 Automatic Dark Mode:** The entire interface seamlessly switches to a dark theme based on your device settings.
- **📅 Nepali Calendar (BS) Support:** Dropdowns automatically adjust the number of days (30, 31, or 32) based on the selected Nepali Year and Month (2060 - 2090 BS).
- **🔢 Numeric Keypads on Mobile:** Tapping the Principal or Rate fields opens the numeric keypad, not the full keyboard.
- **🚫 No Annoying Popups:** Invalid inputs turn red with a subtle animation and an inline error message instead of using standard browser alerts.
- **📐 Detailed Math Breakdown:** Shows exactly how the interest was calculated period by period.
- **⚡ Zero Dependencies:** Built with pure Vanilla JavaScript, HTML, and CSS. No frameworks or libraries required.

## 🚀 How to Use
1. Enter the **Principal amount** (in ₹).
2. Enter the **Monthly interest rate** (%).
3. Select the **Start Date** and **Return Date** using the BS Year, Month, and Day dropdowns.
4. Click **Apply** to view the detailed breakdown, total interest, and total repayment amount.

## 🛠️ Built With
- **HTML5** (Semantic layout)
- **CSS3** (Flexbox, CSS Grid, Media Queries, CSS Variables for theming)
- **Vanilla JavaScript** (No external libraries)

## 📂 Local Setup
If you want to run this project locally on your computer:
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/nepali-interest-calculator.git
