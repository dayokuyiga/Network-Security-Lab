# Network-Security-Lab

## Objective
The Network Security Lab project is established to analzye and undertsand network security operations by using SimSpace and Nmap for netowrk scanning and host directory. This project is aimed to simulate the assessment of network infrastuctures, detect active hosts, and identify potential vulneralbilities in a controlled environment. 
### Skills Learned
- Logging in and managing virtual machines.
- Understanding IP addressing and subnet scanning.
- Executing verbose scans.
- Development of executing commands in Powershell and basic CLI operations.
- Knowledge of ping sweeps.

### Tools Used
- Nmap (Network Mapper)
- Powershell
- Network Map

## Steps
### Screenshot 1: I selected virtual machines and clicked on “Network Map.” The network map is a visualization of the range of virtual machines.
![Screenshot 2024-10-09 161531](https://github.com/user-attachments/assets/82fa2383-1f86-4274-ac35-0ed299b34522)


### Screenshot 2: I successfully logged into a “win-hunt-xxx” virtual machine. I chose to login into WIn-hunt-01.
![Screenshot 2024-10-09 161851](https://github.com/user-attachments/assets/84cbd2f1-e282-44af-92e6-d89c7e115df2)


### Screenshot 3: I opened up the Powershell window from the control center and then typed in “Nmap.”
![Screenshot 2024-10-09 162422](https://github.com/user-attachments/assets/05a2bce4-043d-4056-8cab-d14cd3fb0b4a)


### Screenshot 4: I hit return on the command “nmap,” and Powershell lists the switches that I can use with nmap.
![Screenshot 2024-10-09 162501](https://github.com/user-attachments/assets/2ba0877b-095c-4291-9e1c-454e438c2901)


### Screenshot 5: I executed the command in Powershell -v 172.16.3.0/24.
![Screenshot 2024-10-09 162635](https://github.com/user-attachments/assets/d12b1be1-f20c-440c-a040-6a3f270229b1)


### Screenshot 6: After executing the output of my first scan by typing nmap -v 172.16.3.0/24, I see many closed ports.
![Screenshot 2024-10-09 163013](https://github.com/user-attachments/assets/1483e36f-2d75-4900-a022-c98ea55977a6)


### Screenshot 7: I initiated my next step by typing nmap -v 172.16.3.0/24> yournamescan1.txt.
![Screenshot 2024-10-09 164038](https://github.com/user-attachments/assets/03b5d400-4478-46c7-bccb-8c64d1c0b819)


### Screenshot 8: I used the “ls” command to list all my files in the same directory.
![Screenshot 2024-10-09 164123](https://github.com/user-attachments/assets/e46a0718-2c7f-4c4a-8964-4ee775a43452)


### Screenshot 9: I then used the command “cat yournamescan1.txt to see my output type.
![Screenshot 2024-10-09 164547](https://github.com/user-attachments/assets/8c5b2865-2f99-4ff2-93ce-c52d7f150627)


### Screenshot 10: The command “cat yournamescan1.txt” shows how many addresses nmap say in the scan. Nmap shows that there are 256 IP addresses that popped up in the scan 172.16.3.0/24 subnet.
![Screenshot 2024-10-09 164835](https://github.com/user-attachments/assets/a2ccbfc3-5ba7-4f30-889f-ca38f08165a0)


### Screenshot 11: The command “cat yournamescan1.txt” also shows how many hosts nmap says in the scan. Nmap shows that 37 hosts popped up in the scan 172.16.3.0/24 were up.
![Screenshot 2024-10-09 164845](https://github.com/user-attachments/assets/2b851bcd-7bfa-4d35-bccf-d3811a3e4e0c)


### Screenshot 12: This shows the other subnets on the range.
![Screenshot 2024-10-09 165239](https://github.com/user-attachments/assets/60ef536d-1ffd-46b4-868d-17045101b31c)


### Screenshot 13: I executed nmap –v –sU 172.16.2.2 > yournamemachine10scan.txt to see which ports are open and which ones are not open.
![Screenshot 2024-10-09 165617](https://github.com/user-attachments/assets/99887a30-2244-45bc-afa0-3cfd046efc13)


### Screenshot 14: I used the -sU switch to scan for open ports. After that, I used the command y nmap -v -sn 172.16.2.2 to see the difference. The command sn command only checks if the host is online but does not scan for open ports.
![Screenshot 2024-10-09 165803](https://github.com/user-attachments/assets/0dc9a5dc-8351-4c36-accf-8d71b6f90f12)
