**🚗 Web Scraping for Automotive Service Pricing – Perodua Service Maintenance**

**🔍 Project Overview**
This project automates the extraction of service pricing details for Perodua vehicles from the official Perodua website using Selenium and Pandas. It retrieves pricing for different car variants and service intervals, allowing for easy comparison and analysis.

**📊 Extracted Data**
The script scrapes the following details:

Car Variant (e.g., Myvi, Axia, Bezza)
Service Interval (e.g., 5,000 km, 10,000 km, etc.)
Service Items (e.g., engine oil, oil filter)
Pricing Details:
CVT & Manual transmission
Peninsular Malaysia & East Malaysia prices

**🛠️ Tech Stack**
Python 🐍
Selenium (Web scraping)
Pandas (Data processing)
Chrome WebDriver

**🚀 How to Run the Script**
1️⃣ Install Dependencies
Ensure you have Python installed, then install the required libraries:

pip install selenium pandas

2️⃣ Download Chrome WebDriver
Make sure your ChromeDriver version matches your Google Chrome version. Download here.

3️⃣ Run the Script
Execute the Python script:

python perodua_scraper.py

4️⃣ Output
The extracted data is automatically saved as a .csv file in:
📂 C:\Users\Syazwani\Desktop\syazwani\PERODUA_PROJECT

**📂 Folder Structure**

📂 Web-Scraping-for-Automotive-Service-Pricing
 ┣ 📂 data                # Sample extracted CSV files
 ┣ 📂 scripts             # Python script(s)
 ┣ 📜 README.md           # Project documentation
 ┣ 📜 requirements.txt     # Python dependencies
 ┗ 📜 .gitignore          # Excludes unnecessary files
 
**📌 Sample Output**
Car Variant	Service Interval	Service Item	CVT Price (Pen)	CVT Price (EM)	Manual Price (Pen)	Manual Price (EM)
Myvi	10,000 km	Engine Oil	RM 183.90	RM 192.00	RM 0.00	RM 0.00

**💡 Why This Project?**
This project demonstrates real-world data extraction skills useful for:
✅ Automating Data Collection
✅ Data Analysis & Pricing Trends
✅ Web Scraping with Selenium

🏗 Future Improvements
📌 Automate daily/weekly scraping
📊 Build a visual dashboard (e.g., using Power BI, Streamlit)
📡 API integration for live updates
🤝 Connect with Me
📌 LinkedIn: Your LinkedIn Profile
📂 Portfolio: Your Portfolio
