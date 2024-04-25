# Metasploit-for-reconnaissance
# Metasploit
Metasploit for reconnaissance in pentesting

# AIM:

To get introduced to Metasploit Framework and to  perform reconnaissance  in pentesting .

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
Find out the ip address of the attackers system

## OUTPUT:
![image](https://github.com/R-Guruprasad/Metasploit-for-reconnaissance/assets/119390308/13c6084a-9d91-412f-ad9f-2abf5157fd87)

Invoke msfconsole
![image](https://github.com/R-Guruprasad/Metasploit-for-reconnaissance/assets/119390308/039dba9e-2070-4ce3-9c47-67bb09a8c8a5)

## Port scanning:
msf > nmap -sT 192.168.1810/24-p1-1000

![image](https://github.com/R-Guruprasad/Metasploit-for-reconnaissance/assets/119390308/42a5998b-162f-4260-a053-0b380b9969ca)

msf > db_nmap 192.168.181.0/24

![image](https://github.com/R-Guruprasad/Metasploit-for-reconnaissance/assets/119390308/36c1ae18-c104-43c0-9720-ef79d81adba2)

ls -l

![image](https://github.com/R-Guruprasad/Metasploit-for-reconnaissance/assets/119390308/3b4618cc-659a-4764-8d98-066825fbd609)

search

![image](https://github.com/R-Guruprasad/Metasploit-for-reconnaissance/assets/119390308/c4a6a6de-94c2-499f-ab63-46cd5c7fc5c0)

info 

![image](https://github.com/R-Guruprasad/Metasploit-for-reconnaissance/assets/119390308/38ebdf7e-db11-415b-9333-c7734d43727a)

## MYSQL ENUMERATION

db_nmap -sV -sC -p 3306 <metasploitable_ip_address>

![image](https://github.com/R-Guruprasad/Metasploit-for-reconnaissance/assets/119390308/d3a91db0-3490-462d-a685-5dee44e8423f)

search

![image](https://github.com/R-Guruprasad/Metasploit-for-reconnaissance/assets/119390308/0097f8ca-f157-441b-946c-164fb9a3ead7)

Use the set rhosts command to set the parameter and run the module, as follows:

![image](https://github.com/R-Guruprasad/Metasploit-for-reconnaissance/assets/119390308/b0bccd06-5bec-42ff-9a7a-751e6c33312e)
![image](https://github.com/R-Guruprasad/Metasploit-for-reconnaissance/assets/119390308/040a1541-e34b-49e2-8fb3-0e5575d7c54a)

After scanning, you can also brute force MySQL root account via Metasploit's auxiliary(scanner/mysql/mysql_login) module

![image](https://github.com/R-Guruprasad/Metasploit-for-reconnaissance/assets/119390308/5506ff5f-aaf0-47a9-8f2d-ca32589a9a3a)

/usr/share/wordlists: set PASS_FILE /usr/share/wordlistss/rockyou.txt

![image](https://github.com/R-Guruprasad/Metasploit-for-reconnaissance/assets/119390308/1911deda-3b8b-42ae-91e9-cf40f452e81d)

## RESULT:
The Metasploit framework for reconnaissance is  examined successfully

