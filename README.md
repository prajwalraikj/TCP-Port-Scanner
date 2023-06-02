# TCP-Port-Scanner
This code is a multi-threaded TCP port scanner that scans for open ports on a specified target. The user 
inputs the target IP address and the program scans the specified ports, using the ports information provided in a JSON file. 
The program then prints a table of any open ports found. The program also includes a feature that runs the scanner every 
5 minutes for an hour and checks the site status. The program utilizes the socket library to create TCP connections and the 
threading library to perform multi-threading. The pyfiglet and rich libraries are used to display stylized text and tables in 
the console. 
