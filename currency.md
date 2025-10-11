# 💱 Currency Converter (Node.js)

A simple **command-line currency converter** built using **Node.js**, **HTTPS API requests**, and **chalk** for colorful output.  
It converts USD to any target currency (e.g., INR, EUR, NPR) using real-time exchange rates.

---

## 🚀 Features
- Converts from **USD** to any target currency.  
- Uses **live exchange rates** from [ExchangeRate-API](https://www.exchangerate-api.com/).  
- Beautiful **colored terminal output** using Chalk.  
- Handles **invalid inputs** and **API errors** gracefully.

---

## 🛠️ Technologies Used
- Node.js (ES Modules)
- HTTPS (built-in)
- Readline (built-in)
- Chalk (for terminal styling)
- ExchangeRate-API (for currency data)

---

## 📸 Output Example

Below is an example of the working program:

![Currency Converter Output](output.png)

---

## 🧩 Installation & Setup

1. **Clone this repository**  
   ```bash
   git clone https://github.com/yourusername/currency-converter.git
   cd currency-converter
Install dependencies

npm install chalk
Add your ExchangeRate API key
Get your free API key from https://www.exchangerate-api.com

Then replace the value inside the code:
const apiKey = "YOUR_API_KEY_HERE";
Run the project
node currency_converter.js

💡 Example Usage
Enter the amount in USD: 10
Enter the target currency (e.g., INR, EUR, NPR): inr
10 USD is approximately 887.48 INR

⚠️ Notes

Ensure you have a valid API key; otherwise, you'll receive an HTML or error response.

Works with Node.js 18+.

👩‍💻 Author

Mahnoor Muhammad Naeem
📧 Email: mahnoormuhammadnaeem99@gmail.com

🌐 GitHub: Mahnoor-Muhammad-Naeem


✅ **How to attach the screenshot:**  
Make sure your screenshot file (`output.png`) is saved in the **same folder** as your `README.md` file.  
GitHub will automatically display it inside the README when you push it to your repo.

