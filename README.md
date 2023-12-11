# Noroff
# Back-end Development Year 2
### Information Security - Course Assignment Project<sup>V1</sup>
---

# Application Installation and Usage Instructions
1. Click *Code* (Green button top right) and then *Download ZIP*.
2. Extract the ZIP file in the location of your choosing.
3. Run *start.bat* OR run *npm install* and then *npm start* in the terminal from the selected folder.
4. Navigate you browser to *http://localhost:3000*

# Environment Variables
ADMIN_USERNAME = "isccaowner"  
ADMIN_PASSWORD = "iscca1234"  
DATABASE_NAME = "clubdb"  
DIALECT = "mysql"  
DIALECTMODEL = "mysql2"  
PORT = "3000"  
HOST = "localhost"

# Additional Libraries/Packages
- connect-flash ^0.1.1
- connect-sqlite3 ^0.9.13
- cookie-parser ~1.4.4
- debug ~2.6.9
- dotenv ^16.0.3
- ejs ^3.1.8
- express ^4.18.2
- express-session ^1.17.3
- http-errors ~1.6.3
- morgan ~1.9.1
- mysql ^2.18.1
- mysql2 ^2.3.3
- passport ^0.6.0
- passport-local ^1.0.0
- sequelize ^6.27.0
- sqlite3 ^5.0.2

# NodeJS Version Used
Node.js v18.17.1

# DATABASE
CREATE DATABASE clubdb;

# DATABASEACCESS
CREATE USER IF NOT EXISTS 'isccaowner'@'localhost' IDENTIFIED BY 'iscca1234';  
GRANT ALL PRIVILEGES ON clubdb.* TO 'isccaowner'@'localhost';

# REFERENCES
Friends Vectors by Vecteezy: https://www.vecteezy.com/free-vector/friends
