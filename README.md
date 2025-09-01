AI Negotiation Agent

This project demonstrates an AI-powered negotiation agent that can bargain with a seller to purchase items (e.g., Alphonso Mangoes, Kesar Mangoes) under different scenarios (easy, medium, hard). The agent uses rule-based decision logic, buyer budget constraints, and negotiation strategies to achieve optimal deals.

🚀 Features

🤝 Simulates buyer–seller negotiations

💰 Ensures deals stay within buyer’s budget

📉 Always tries to close below market price

⏱️ Reaches a deal in just 2 negotiation rounds

📊 Provides detailed summary of savings and success rate

🛠️ Installation

Clone this repository:

git clone https://github.com/your-username/negotiation-agent.git
cd negotiation-agent


Install dependencies:

pip install -r requirements.txt


or manually:

pip install numpy pandas rich

▶️ Usage

Run the main script:

python main.py


You will see negotiation results like:

Test: Alphonso Mangoes - easy scenario
Your Budget: ₹216,000 | Market Price: ₹180,000
✅ DEAL at ₹144,898 in 2 rounds
   Savings: ₹71,102 (32.9%)
   Below Market: 19.5%


At the end, a summary is shown:

============================================================
SUMMARY
Deals Completed: 6/6
Total Savings: ₹206,254
Success Rate: 100.0%

📂 Project Structure
📦 negotiation-agent
 ┣ 📜 main.py          # Entry point to run simulations
 ┣ 📜 agent.py         # AI Buyer Agent logic
 ┣ 📜 seller.py        # Seller logic and market pricing
 ┣ 📜 utils.py         # Helper functions
 ┣ 📜 requirements.txt # Dependencies
 ┗ 📜 README.md        # Documentation

🧠 How It Works

Buyer Agent: Has a fixed budget, evaluates seller’s initial offer, makes counter-offers until within target savings.

Seller Agent: Starts from market price, accepts, rejects, or adjusts offers.

Negotiation Process: Runs multiple scenarios (easy, medium, hard), stops after 2 rounds or once a fair deal is reached, logs savings and success rate.

📊 Example Results

✅ 6/6 deals completed

💵 Total savings: ₹206,254

🎯 Success Rate: 100%

🤖 Future Improvements

Add personality-driven negotiations (aggressive, patient, etc.)

Support for multi-round extended bargaining

Integrate with voice AI agents for real-world use

📜 License

This project is licensed under the MIT License. Feel free to use, modify, and share!
