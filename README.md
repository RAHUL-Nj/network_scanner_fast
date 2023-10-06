<img width="348" alt="Screenshot 2023-10-06 203355" src="https://github.com/RAHUL-Nj/network_scanner_fast/assets/98076310/a06cc206-ff94-4813-a49e-a9dea1cdf9b9">



Open a Terminal:

Open a terminal on your Kali Linux system. You can usually do this by clicking on the terminal icon on the desktop or using a keyboard shortcut like Ctrl+Alt+T.
Navigate to the Directory:

Navigate to the directory where your Python script is located using the cd (change directory) command. For example, if your script is in the "Documents" directory, use the following command:
bash
Copy code

cd /path/to/network_scanner.py

Run the Script:

Run the Python script using the python3 command. Assuming your script is named network_scanner.py, use the following command:
bash
Copy code

python3 network_scanner.py 192.168.1.0/24 1-100
Replace 192.168.1.0/24 and 1-100 with the appropriate IP range and port range you want to scan.

Keep in mind that you may need to adjust the permissions to execute the script. You can do this using the chmod command. For example:

bash
chmod +x network_scanner.py


Make sure you have the necessary permissions to run the script and that Python and the required libraries (scapy) are installed on your Kali Linux system.
