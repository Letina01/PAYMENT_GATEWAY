Features
Seamless payment integration with Stripe, Razorpay, PayPal, and Coinbase
Secure transaction handling with Next.js API routes
Environment variable support for sensitive credentials
Fully functional UI for testing payments
🛠️ Tech Stack
Frontend: Next.js 14, React
Backend: Next.js API routes
Payment Providers: Stripe, Razorpay, PayPal, Coinbase
📌 Installation & Setup
Clone the repository:

bash
Copy
Edit
git clone https://github.com/Letina01/PAYMENT_GATEWAY
cd repo-name
Install dependencies:

bash
Copy
Edit
npm install
Configure environment variables:
Create a .env.local file in the root directory and add the required API keys:

env
Copy
Edit
STRIPE_SECRET_KEY=your_stripe_key
RAZORPAY_KEY_ID=your_razorpay_key
PAYPAL_CLIENT_ID=your_paypal_key
COINBASE_API_KEY=your_coinbase_key
Run the development server:

bash
Copy
Edit
npm run dev
The app will be available at http://localhost:3000.

🎯 Usage
Navigate to the payment page.
Choose a payment method (Stripe, Razorpay, PayPal, or Coinbase).
Complete the transaction and view the response.
📷 Screenshots
(Add relevant screenshots of the UI here)

🤝 Contributing
Contributions are welcome! Feel free to open issues and pull requests.

📜 License
This project is licensed under the MIT License.
