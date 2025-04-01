# software-engineering-assignment-2
Automated File Organization System
Project Overview
This project demonstrates the implementation of software design principles using Linux utilities and shell scripting. The system automates file organization by scanning a specified directory, categorizing files based on their types, and moving them into designated subdirectories (e.g., Documents, Images, Videos, Archives, and Executables).

Key Features
Abstraction: The project is divided into key functionalities such as file scanning, sorting, logging, error handling, and scheduling.

Encapsulation: Tasks are structured into separate scripts (e.g., file_scanner.sh, file_mover.sh, logger.sh).

Modularity: Each script is independent, enabling easy maintenance and reuse.

Cohesion & Coupling: High cohesion ensures well-defined tasks, while low coupling minimizes dependencies.

Automation: Uses cron jobs to schedule file organization at regular intervals.
Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/user/repo.git
Grant execution permissions:

bash
Copy
Edit
chmod +x *.sh
Set up the cron job:

bash
Copy
Edit
crontab -e
Add the following line to automate execution every 10 minutes:

bash
Copy
Edit
*/10 * * * * /path/to/file_scanner.sh
Team Members
1)Thakur Digvijay Singh - 23BCS
2)Mayank - 23BCS
3)Paras - 23BCS
4)Shashi Bhushan Thakur - 23BCS10663
5)Kishan - 23BCS
