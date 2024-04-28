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
![71](https://github.com/viswapriyaG/creating-a-backdoor-with-SET/assets/131427787/4d5f0669-1c23-4c80-b274-13bdc8f59883)

It displays the following menu and select 2 for Website Attack Vectors:
![72](https://github.com/viswapriyaG/creating-a-backdoor-with-SET/assets/131427787/b92b71f9-afed-451c-94ed-96ab05280997)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:
![73](https://github.com/viswapriyaG/creating-a-backdoor-with-SET/assets/131427787/690734b0-7d32-4246-9d60-15278882c5b2)


The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
![74](https://github.com/viswapriyaG/creating-a-backdoor-with-SET/assets/131427787/85dca0f7-7b0a-45ad-bfe9-96b217452114)


It shows the following screen in which the ip address of the attacker need to be given which is the default value:
![75](https://github.com/viswapriyaG/creating-a-backdoor-with-SET/assets/131427787/f491f3a4-37ca-43df-8055-852078a4affb)

It shows the following screen in which the option Google can be selected:
![76](https://github.com/viswapriyaG/creating-a-backdoor-with-SET/assets/131427787/ee557e6f-87c0-4750-9582-ff2f92ebe8c6)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
![77](https://github.com/viswapriyaG/creating-a-backdoor-with-SET/assets/131427787/a2a1b592-8d8d-4803-8676-a25385040974)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password
![78](https://github.com/viswapriyaG/creating-a-backdoor-with-SET/assets/131427787/108f46b3-2760-433e-be7b-99dd869245b1)

SET logs the information regarding the Google credentials:
![79](https://github.com/viswapriyaG/creating-a-backdoor-with-SET/assets/131427787/22bfa4c0-ccf4-4c93-9fd9-e1a1de87d1a9)

SET logs the information in the xml file under /root/.set directory:
![80](https://github.com/viswapriyaG/creating-a-backdoor-with-SET/assets/131427787/96381580-60a9-483c-ab79-e34acc930d91)


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
