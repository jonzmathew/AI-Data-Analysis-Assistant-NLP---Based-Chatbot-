# AI-Data-Analysis-Assistant-NLP---Based-Chatbot-
AI Data Analysis Assistant built with Python, Hugging Face Transformers, SpaCy, and Gradio. This tool allows users to upload a CSV dataset and perform analysis (descriptive statistics, correlation, and regression) using natural language prompts. The system automatically classifies the user query, extracts variables from prompt and  give analysis.

🤖 AI Data Analysis Assistant

An AI-powered data analysis tool that allows users to analyze datasets using natural language prompts.
The system automatically identifies the type of analysis required and performs statistical operations such as descriptive statistics, correlation analysis, and regression modeling.

Users simply upload a CSV dataset and ask a question, and the AI assistant processes the request and returns the analysis results.

🚀 Project Overview

Traditional data analysis requires writing queries or code to explore datasets. This project simplifies the process by enabling users to interact with their data using natural language queries.

The system uses Natural Language Processing (NLP) to understand user prompts, extract relevant variables, determine the appropriate statistical method, and execute the analysis automatically.

This makes data analysis more accessible for users who may not have strong programming or statistical backgrounds.

✨ Features

✔ Upload and analyze CSV datasets
✔ Perform Descriptive Statistics
✔ Compute Correlation between variables
✔ Run Linear Regression analysis
✔ Natural Language Prompt Based Analysis
✔ Automatic analysis type detection using AI
✔ Interactive web interface using Gradio

🧠 How It Works

User uploads a CSV dataset.

User enters a natural language query such as:

"Show correlation between sales and marketing spend"

"Run regression between price and demand"

The system uses Zero-Shot Classification to determine the type of analysis.

SpaCy NLP extracts the relevant variables from the prompt.

The requested statistical analysis is executed using Pandas and Scikit-learn.

Results are displayed through a Gradio interface.

🛠 Tech Stack

Programming Language

Python

Libraries & Frameworks

Pandas

NumPy

Scikit-learn

Hugging Face Transformers

SpaCy

Gradio

Machine Learning / NLP

Zero-Shot Classification

Natural Language Processing

Linear Regression

📊 Example Use Cases

Example prompts a user can enter:
Show descriptive statistics of the dataset, 
Find correlation between age and income, 
Run regression between advertising spend and sales

The AI assistant will automatically identify the analysis type and generate results.

📂 Project Structure
AI-Data-Analysis-Assistant
│
├── AI Data Analyst Revised.ipynb
├── dataset.csv
├── README.md

⚙ Installation

Clone the repository
git clone https://github.com/yourusername/AI-Data-Analysis-Assistant.git

Navigate to the project folder
cd AI-Data-Analysis-Assistant

Install required libraries
pip install pandas numpy scikit-learn transformers spacy gradio

Run the notebook or Python script.

🖥 Running the Application

Start the Gradio interface and open the local web link generated.

Upload a dataset and start interacting with it using natural language prompts.

🎯 Learning Outcomes

This project demonstrates:

Building AI-driven data analysis tools

Applying NLP for query understanding

Automating statistical analysis workflows

Developing interactive ML applications

📈 Future Improvements

Add data visualization (Matplotlib / Plotly)

Support more statistical models

Implement LLM-based query understanding

Deploy the application on Hugging Face Spaces or Streamlit Cloud

👨‍💻 Author

Johns M

Aspiring Data Analyst / Data Scientist passionate about AI, data analytics, and machine learning.

⭐ If you like this project, consider starring the repository.

✅ If you want, I can also give you 3 things that will make this project look MUCH more impressive to recruiters, like:

Adding visualizations

Adding AI chatbot style interaction

Making it look like a real SaaS analytics tool
