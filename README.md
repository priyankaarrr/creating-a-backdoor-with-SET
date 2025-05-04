# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode


### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. 
The command sudo setoolkit in the prompt gives menu with set prompt:

## output

![image](https://github.com/user-attachments/assets/6eaf3815-ce59-4f4e-be7d-0580a3c2cb5b)

The command sudo setoolkit in the prompt gives menu with set prompt. Select menu 1 for Social Engineering Attacks.
It displays the following menu and select 2 for Website Attack Vectors:

## OUTPUT:
![image](https://github.com/user-attachments/assets/eed600ab-83fa-47c6-ba4d-b19ad5b3d262)

The website Attack Vectors displays the following menu. In this menu, 3 for Credential Harvester Attack Method is selected:

## OUTPUT:
![image](https://github.com/user-attachments/assets/0ac00dd5-9df7-4d8b-afc1-99f79b26d6f2)

The Credential Harvester Attack Method displays the following menu. In this menu, 1 for Web Templates is selected:

## OUTPUT:
![image](https://github.com/user-attachments/assets/890dc9b7-b68f-436b-b054-bf5d47adac32)
The Credential Harvester Attack Method displays the following menu. In this menu, 1 for Web Templates is selected.
It shows the following screen in which the IP address of the attacker needs to be given (default value):

## OUTPUT:
![image](https://github.com/user-attachments/assets/46ca7edc-99e4-4360-bca1-8c4a5bef32f5)
It shows the following screen in which the option Google can be selected:

## OUTPUT:
![image](https://github.com/user-attachments/assets/c03419e2-e10b-42dd-9102-df04964c677c)
SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

## OUTPUT:
![image](https://github.com/user-attachments/assets/cb41ba9d-5815-49b2-a9be-18374bf55dea)
In Windows IE, on giving the URL http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password.

## OUTPUT:
![image](https://github.com/user-attachments/assets/b23e6afe-fab3-4c55-8c89-7f3486c9e2f9)
SET logs the information regarding the Google credentials:

## OUTPUT:
![image](https://github.com/user-attachments/assets/16e30fe2-c796-40f8-ba73-3772d6649b4c)
SET logs the information in the XML file under /root/.set directory:

## OUTPUT:
![image](https://github.com/user-attachments/assets/e72e91da-2fe8-45ca-a4dc-cba46e5885dd)


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
