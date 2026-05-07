💬 Loan Transaction Chatbot – AI Powered Insights

An intelligent AI-powered chatbot built using Python, Streamlit, NLP, and Semantic Search to analyze and explore loan application data interactively.

This project allows users to ask natural language questions about loan applications, fraud cases, approved/rejected loans, customer profiles, and more.

🚀 Features
✅ Natural Language Query Support
✅ AI-Powered Semantic Search using Sentence Transformers
✅ Fraud Detection Insights
✅ Loan Approval/Rejection Analysis
✅ Dynamic Filtering with Conditions
✅ Interactive Streamlit UI
✅ Fast Embedding-Based Search
✅ Real-Time Data Exploration
🧠 Technologies Used
Python
Streamlit
Pandas
NumPy
Sentence Transformers
Machine Learning / NLP
Semantic Search
Pickle
📂 Project Structure
loan_chatbot/
│
├── loan_chatbot.py
├── loan_applications.csv
├── loan_transactions.csv
├── embeddings.pkl
├── embeddings_fast.pkl
├── Loan-Transaction-Chatbot-AI-Powered-Insights.pptx
└── README.md
⚙️ Installation
1️⃣ Clone the Repository
git clone https://github.com/your-username/loan-transaction-chatbot.git
cd loan-transaction-chatbot
2️⃣ Install Dependencies
pip install -r requirements.txt

If you don't have a requirements file, install manually:

pip install streamlit pandas numpy sentence-transformers
▶️ Run the Application
streamlit run loan_chatbot.py

The app will open in your browser.

💡 Example Queries

Try asking questions like:

show male applications
show female applications and cibil score > 700
show other applications and age < 30
show male home loan applications and monthly income > 50000
show fraud applications
how many approved applications
show rejected applications
🔍 How It Works
✅ 1. Data Loading

The chatbot loads loan application data from CSV files.

✅ 2. Column Standardization

Dataset columns are cleaned and renamed for consistency.

✅ 3. Semantic Context Creation

Each loan record is converted into meaningful text context.

✅ 4. Embedding Generation

Sentence Transformer model converts text into vector embeddings.

✅ 5. Smart Query Handling

The chatbot:

Detects conditional filters
Performs semantic similarity search
Returns matching applications
Displays fraud, approved, and rejected cases
📊 Key Functionalities
🔹 Condition-Based Filtering

Supports filters like:

Gender
Age
Loan Amount
Monthly Income
CIBIL Score
Interest Rate
Employment Status
Loan Type
🔹 Fraud Analysis

Displays:

Fraudulent applications
Fraud types
Fraud counts
🔹 Semantic Search

Uses AI embeddings to understand user intent and provide the best matching result.

🖥️ Streamlit User Interface

The application provides a simple and interactive interface where users can:

Enter natural language queries
View filtered loan applications
Analyze fraud cases
Explore approval/rejection patterns
📈 Future Enhancements
✅ Dashboard Visualizations
✅ Voice-Based Queries
✅ Chat History
✅ Multi-Dataset Support
✅ Loan Recommendation System
✅ Real-Time Database Integration
✅ Advanced Fraud Prediction Model
🎯 Use Cases

This project can be used for:

Banking Analytics
Financial Fraud Analysis
Loan Risk Assessment
AI Chatbot Demonstration
NLP & Semantic Search Learning
Final Year Data Science Projects
👨‍💻 Author
Tharun R

Aspiring Data Analyst & Machine Learning Enthusiast

Skills:

SQL
Python
Power BI
Machine Learning
NLP
Streamlit
