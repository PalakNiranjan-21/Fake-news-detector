# Fake-news-detector
This is a Java-based GUI application that allows users to verify if a given news headline is real or fake. It simulates the logic using a dummy API and logs the check into a MySQL database.
📦 Technologies Used:
- Java
- Swing (GUI)
- MySQL (Database)
- JDBC (Java Database Connectivity)
- IntelliJ IDEA
- Threads (Multithreading)
- GitHub for version control

📁 Project Structure:
- MainApp.java → GUI code and main method
- ApiCaller.java → Contains logic for checking headline
- DatabaseManager.java → Manages DB connection and insert
- model/NewsRecord.java (Optional model)
- README.txt → This file
- Screenshots/ → GUI, MySQL, and terminal screenshots

🗃️ Database Details:
- Database Name: `fake_news_db`
- Table: `news_checks`
- Schema:
    id INT AUTO_INCREMENT PRIMARY KEY
    headline TEXT
    result TEXT
    checked_at DATETIME DEFAULT CURRENT_TIMESTAMP

⚙️ How to Run the Project:
1. Install MySQL and create database + table using:
2. Open project in IntelliJ IDEA.
3. Add the JDBC `.jar` file to your project via:
File > Project Structure > Libraries > + Add JAR
4. Set your DB username/password in `DatabaseManager.java`.
5. Run `MainApp.java`.
6. Enter a headline and click `Check`. The result will be shown and saved to MySQL.

📌 Notes:
- Use XAMPP/MySQL as DB server (as per college guidelines).
- JDBC multithreading ensures the GUI doesn’t freeze.
- Code is modular and commented properly.

🔗 GitHub:
Make sure to upload the full project with screenshots and this README to GitHub.

Set the repo as public and share the link in your presentation.

👥 Developed By:📦 Technologies Used:
- Java
- Swing (GUI)
- MySQL (Database)
- JDBC (Java Database Connectivity)
- IntelliJ IDEA
- Threads (Multithreading)
- GitHub for version control

📁 Project Structure:
- MainApp.java → GUI code and main method
- ApiCaller.java → Contains logic for checking headline
- DatabaseManager.java → Manages DB connection and insert
- model/NewsRecord.java (Optional model)
- README.txt → This file
- Screenshots/ → GUI, MySQL, and terminal screenshots

🗃️ Database Details:
- Database Name: `fake_news_db`
- Table: `news_checks`
- Schema:
    id INT AUTO_INCREMENT PRIMARY KEY
    headline TEXT
    result TEXT
    checked_at DATETIME DEFAULT CURRENT_TIMESTAMP

⚙️ How to Run the Project:
1. Install MySQL and create database + table using:
2. Open project in IntelliJ IDEA.
3. Add the JDBC `.jar` file to your project via:
File > Project Structure > Libraries > + Add JAR
4. Set your DB username/password in `DatabaseManager.java`.
5. Run `MainApp.java`.
6. Enter a headline and click `Check`. The result will be shown and saved to MySQL.

📌 Notes:
- Use XAMPP/MySQL as DB server (as per college guidelines).
- JDBC multithreading ensures the GUI doesn’t freeze.
- Code is modular and commented properly.

🔗 GitHub:
Make sure to upload the full project with screenshots and this README to GitHub.

Set the repo as public and share the link in your presentation.

👥 Developed By:
[Palak Niranjan-24SCSE1280057]
- Course: B.Tech CSE 
- College: [Galgotias university]
