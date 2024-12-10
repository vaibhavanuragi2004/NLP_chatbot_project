Chatbot using NLP
Overview
This project implements a friendly and engaging chatbot using Natural Language Processing (NLP) techniques. The chatbot is designed to understand user intents and provide informative responses based on predefined patterns and responses. It utilizes the nltk library for natural language processing, scikit-learn for machine learning, and streamlit for creating an interactive web interface.

Features
Understands various user intents and provides helpful responses.
Engages in informative and engaging conversations.
Maintains a conversation history for easy reference.
Built using Python and leverages popular libraries for NLP and machine learning.
Technologies Used
Python
NLTK
Scikit-learn
Streamlit
JSON for intents data
Installation
1. Clone the Repository
Bash
git clone <repository-url>
cd <repository-directory>
Use code with caution.

2. Create a Virtual Environment (Optional but Recommended)
Bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
Use code with caution.

3. Install Required Packages
Bash
pip install -r requirements.txt
Use code with caution.

4. Download NLTK Data
Python
import nltk
nltk.download('punkt')
Use code with caution.

Usage
To run the chatbot application, execute the following command:

Bash
streamlit run app.py
Use code with caution.

Once the application is running, you can interact with the chatbot through the web interface. Type your message in the input box and press Enter to see the chatbot's response.

Intents Data
The chatbot's behavior is defined by the intents.json file, which contains various tags, patterns, and responses. You can modify this file to add new conversation topics or change existing ones.

Conversation History
The chatbot saves the conversation history in a CSV file (chat_log.csv). You can view past interactions by selecting the "Conversation History" option in the sidebar (if applicable).

Contributing
Contributions to this project are welcome! If you have suggestions for improvements or features, feel free to open an issue or submit a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments
NLTK for natural language processing.
Scikit-learn for machine learning algorithms.
Streamlit for building the web interface.
The revisions focus on the chatbot's helpfulness and ability to engage in informative conversations, while removing any reference to illnesses.
