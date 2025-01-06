# Cold-Email-Generator-Using-GenAI

# 📧 Cold Email Generator

Cold Email Generator is a tool designed to streamline business development efforts by automating the creation of personalized cold emails. Built using advanced generative AI technologies, this tool analyzes job postings from company career pages and crafts tailored outreach emails, complete with relevant portfolio links and resources.

## **🚀 Key Features**
- Extracts job listings directly from company career pages using their URL.
- Generates personalized cold emails tailored to specific job descriptions.
- Dynamically includes relevant portfolio links from a vector database.
- User-friendly interface powered by **Streamlit**.

## **💡 Use Case Example**
Imagine this scenario:

- **Nike** is hiring a Principal Software Engineer and has job postings listed on their careers page.
- **Company X**, a software development company, wants to offer Nike a dedicated software development engineer to meet their needs.
- With this tool, Company X 's business development executive, Mohan, can generate a personalized email that highlights Atliq's services, links to relevant portfolios, and saves time in crafting a high-quality cold email.

## **🏗️ Architecture Overview**
The system architecture is designed to leverage the power of LLMs (like GPT), scraping tools, and vector databases to create seamless email generation workflows.


## **⚙️ Setup Instructions**

### Prerequisites
1. Obtain an API key from **Groq**:
   - Sign up or log in at [Groq API Keys](https://console.groq.com/keys).
   - Generate an API key and store it securely.

2. Update the `.env` file:
   ```plaintext
   GROQ_API_KEY=your_api_key_here
   ```

### Installation Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/harshsharma24/Cold-Email-Generator-Using-GenAI
   ```

2. Navigate to the project directory:
   ```bash
   cd Cold-Email-Generator-Using-GenAI
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Streamlit app:
   ```bash
   streamlit run app/main.py
   ```

## **📖 How to Use**
1. Launch the application.
2. Enter the URL of the company's careers page.
3. View the extracted job listings.
4. Generate personalized emails based on selected job postings.
5. Copy, edit, or download the generated emails.

## **🛠️ Technologies Used**
- **Groq** for natural language processing and vector database integration.
- **LangChain** for orchestrating LLM workflows.
- **Streamlit** for building an interactive and intuitive web interface.
- **Python** for backend logic and data handling.

## **📂 Project Structure**
```
├── app
│   ├── main.py          # Main application entry point
│   ├── utils.py         # Utility functions
│   └── templates        # Email templates
├── data                 # Sample data files
├── imgs                 # Images for documentation
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation
```

## **📜 License**
This project is licensed under the **MIT License**. Attribution is required for all copies or substantial portions of the software.

## **🤝 Contributing**
Contributions are welcome! Feel free to fork the repository and submit a pull request with your improvements.

---

If you find this project helpful, please ⭐ the repository and share it with others!

---

**Author**: Harsh Sharma