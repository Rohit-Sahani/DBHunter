DB Hunter 🛠️




DB Hunter is a Python-based educational tool that automates SQL Injection to enumerate databases, tables, columns, and extract data from vulnerable web applications.

⚠ Disclaimer: For educational purposes only. Do not use on websites you do not own or have explicit permission to test. Unauthorized usage is illegal and unethical.

**Features**

Automatically enumerates databases on vulnerable endpoints.
Enumerates tables for a selected database.
Enumerates columns for a chosen table.
Extracts data from any selected column.
Built with Python, Requests, and BeautifulSoup.

Requirements
Python 3.8+
pip install requests beautifulsoup4

**Usage**

Clone the repository (or if already uploaded, skip this step).
Open DBHunter.py and replace the target URL with your vulnerable lab URL.
Run the script:
python DBHunter.py


Follow the prompts to select database → table → column.
Extracted data will be displayed in the console.
Example Output
[+] Databases found:
   - testdb
   - shopdb

Enter database name: shopdb

[+] Tables found:
   - users
   - orders

Enter table name: users

[+] Columns found:
   - id
   - username
   - email

Enter column name: email

[+] Extracted Data:
   - user1@example.com
   - admin@shop.com

Contributing
Pull requests and issues are welcome.
Suggestions for new features or improvements are appreciated.

License
MIT License – see LICENSE
