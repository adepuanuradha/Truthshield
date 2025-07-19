# Truthshield
**🚨 Truth Shield - Spam & Misinformation Detector**
Truth Shield is an intelligent system designed to detect spam, verify facts, and validate sources like emails and phone numbers. It helps users identify fraudulent content, highlight misinformation, and stay protected from phishing attacks using advanced NLP, Machine Learning, and Web APIs.
🧠 Key Features
📩 Spam Detection
Utilizes a Naïve Bayes Classifier to label text as SPAM or NOT SPAM.
Learns from message patterns and context to accurately flag suspicious content.

✅ Fact Checking
Integrates with the Google Fact Check API to verify claims.
Returns the status of a statement: Verified, Disputed, or Not Found.

🔍 Source Verification
Validates email addresses using the emailrep.io API.
Verifies phone numbers using the Numverify API for authenticity and location info.

⚠️ Misinformation Highlighting
Flags keywords like “fraud,” “scam,” “fake” to alert users of potential red flags.
Uses NLP to emphasize misleading or suspicious terms in the message.

🌐 Related Content Search
Fetches relevant news articles and scam alerts via DuckDuckGo Web Scraping.
Helps users cross-reference and gain more context on messages received.
⚙️ How It Works
User Input: A message, email, or phone number is provided by the user.
Spam Check: The ML model analyzes the text for spam classification.
Fact Verification: Google Fact Check API is queried for claim validation.
Source Validation: EmailRep & Numverify APIs authenticate email and phone number.
Content Highlighting: NLP model highlights misinformation indicators.
Contextual Results: DuckDuckGo scraping displays related news and scam alerts.
Output: All results are shown through an easy-to-use Gradio web interface.

🔍 Use Cases
🔐 Fraud Detection: Identify phishing and scam attempts in real-time.
📰 Fact-Checking Tool: Ideal for journalists, bloggers, and researchers.
🧑‍💻 Everyday Use: General users can validate suspicious emails, texts, or numbers.
