
# Creating-a-backdoor-with-SET
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

 ![image](https://github.com/danush564/creating-a-backdoor-with-SET/assets/98585166/fbcc3da2-3941-4134-8d69-c4a67849ef90)
 It displays the following menu and select 2 for Website Attack Vectors:
![image](https://github.com/danush564/creating-a-backdoor-with-SET/assets/98585166/12375ce7-86e8-4bf4-afc5-1b12f9e3197b)
The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:
 ![image](https://github.com/danush564/creating-a-backdoor-with-SET/assets/98585166/697af74f-64d0-49a9-a686-f1a3ce3bdddb)
 The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
![image](https://github.com/danush564/creating-a-backdoor-with-SET/assets/98585166/bc4215b2-dc2e-40ff-bbc5-a08926231530)
 It shows the following screen in which the ip address of the attacker need to be given which is the default value:
![image](https://github.com/danush564/creating-a-backdoor-with-SET/assets/98585166/6e6f3d7e-9649-465a-be6b-63624bf0f3ad)
 It shows the following screen in which the option Google can be selected:
![image](https://github.com/danush564/creating-a-backdoor-with-SET/assets/98585166/8b45a95c-258c-41f4-95b5-e2b435fecbd2)
 SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
![image](https://github.com/danush564/creating-a-backdoor-with-SET/assets/98585166/f080b397-04d8-49ab-baa7-945c8c01f269)
 In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password 
![image](https://github.com/danush564/creating-a-backdoor-with-SET/assets/98585166/cd021dc6-a349-4581-bc6c-041c20c7d48f)
 SET logs the information regarding the Google credentials:
![image](https://github.com/danush564/creating-a-backdoor-with-SET/assets/98585166/2460664e-7dd8-4950-ab1a-28bad4537573)
 SET logs the information in the xml file under /root/.set directory:
![image](https://github.com/danush564/creating-a-backdoor-with-SET/assets/98585166/bed7f919-6ad8-4608-ae97-db16edf93fa0)
















## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
