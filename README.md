# Automated Port Scan Logger

## Objective
The Automated Port Scan Logger is designed to execute multiple Nmap scans, empowering users to specify both the IPv4 address to be scanned and the Nmap operators to employ. This automated scanner serves a multitude of purposes, including basic penetration testing, network troubleshooting, intrusion detection, and beyond. Crafted in Python, this script offers a versatile solution for enhancing cybersecurity protocols and network management strategies.

### Skills Learned

- Development of Python Programming Proficiency
- Enhancement of Scripting and Automation Abilities
- Application of Nmap Knowledge
- Refinement of Problem-Solving Skills
- Fostering Documentation and Communication

### Tools Used

- Python for script developemnt
- Nmap Library to integrate Nmap and all of its functionality into my code
- Virtual Studio Code as the IDE for effiecient coding

## Scanner In Action
1. After launching the code the user will be prompted for an IPv4 address and their desired Nmap operators.

<img src="https://github.com/WesleyKProfile/Automated-Port-Scan-Logger/assets/168662972/04293f92-87a8-491c-801f-f901506d7d1b" alt="image">

<sub>ref 1: The code is running and the user has entered the IP address for Scanme.nmap.org and the user has entered the operator for a SYN scan(-sS).</sub>


2. Once the Nmap scan has completed the user will be prompted to run more scans. If the user enters case insentive "y" they will be prompted to enter a new IPv4 address and new operators

<img src="https://github.com/WesleyKProfile/Automated-Port-Scan-Logger/assets/168662972/a36dabac-93ee-4564-9fdf-79c5809dda52" alt="image">

<sub>ref 2: The user is now prompted to either continue scanning or end the script.</sub>

3. The script is capable of utilizing more than one Nmap operator at a time. For instance the user could run a SYN scan(-sU) and a UDP scan(-sU) at the same time.

<img src="https://github.com/WesleyKProfile/Automated-Port-Scan-Logger/assets/168662972/bda21b68-e7c4-4e3d-b01a-ed7f3f423958" alt="image">

<sub>ref 3: The image shows the user entering three different operators. The "-A" operator will enable OS detection and Version detection, Script scanning and Traceroute. The "-T4" runs nmap in the second fastest mode. The "-p-" operators scans all ports.</sub>

5. If an invalid IP address or Nmap operator is entered, no scan will be performed and the script will prompt the user if they wish to scan again.

6. The results of the scan are added to a text document named "scan_results.txt" where they are labeled by numerical order and operators used. The document can be updated at anytime. 

<img src="https://github.com/WesleyKProfile/Automated-Port-Scan-Logger/assets/168662972/1385e69e-a221-4d60-bff8-4100ac3bd773" alt="image">

<sub>ref 4: The image shows the organized reults of all three scans</sub>

