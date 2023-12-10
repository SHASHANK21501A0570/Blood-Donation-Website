Enter the command "npm install express mysql body-parser" at the beginning in the terminal to install the required libraries for the server.js file.
Use "MY SQL Workbench" for this project.
Create a new account in the "MY SQL Workbench" with the name as nodeuser and password as nodeuser@1234. Grant all the permissions to this account in the root account.
Now enter the following commands in the workbench.
create database donorlist;
use donorlist;
{
	CREATE TABLE donorlist (
    DonorID INT AUTO_INCREMENT PRIMARY KEY,
    FullName VARCHAR(255) NOT NULL,
    Age INT NOT NULL,
    BloodGroup VARCHAR(10) NOT NULL,
    LastDonationDate DATE NOT NULL
				);
}
You can run the code by entering the command "node server.js" in the terminal.
You need to have node in order to run the commands.
