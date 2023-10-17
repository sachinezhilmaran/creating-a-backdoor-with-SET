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
![image](https://github.com/sachinezhilmaran/creating-a-backdoor-with-SET/assets/128135351/b2fb37d9-c29a-4aff-ad9b-45218a05289f)
It displays the following menu and select 2 for Website Attack Vectors:
![image](https://github.com/sachinezhilmaran/creating-a-backdoor-with-SET/assets/128135351/39a39365-80ed-4288-a2d8-234f296c619f)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

![image](https://github.com/sachinezhilmaran/creating-a-backdoor-with-SET/assets/128135351/2a6b6de4-8f05-4f4b-a0d9-f3a17443c907)


The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

![image](https://github.com/sachinezhilmaran/creating-a-backdoor-with-SET/assets/128135351/0f7ae62d-4d96-4da3-8064-4a170fdda015)


It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![image](https://github.com/sachinezhilmaran/creating-a-backdoor-with-SET/assets/128135351/29e0ae47-761a-4da1-b56a-bff14ca8a178)


It shows the following screen in which the option Google can be selected:

![image](https://github.com/sachinezhilmaran/creating-a-backdoor-with-SET/assets/128135351/aec1c475-fb78-43da-94ea-a9fa3218b8c3)


SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

![image](https://github.com/sachinezhilmaran/creating-a-backdoor-with-SET/assets/128135351/f9846d19-c499-4611-9f6e-43f6e363dd7a)


In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

![image](https://github.com/sachinezhilmaran/creating-a-backdoor-with-SET/assets/128135351/2da57200-babf-4c67-8dea-df2c545d9861)
![image](https://github.com/sachinezhilmaran/creating-a-backdoor-with-SET/assets/128135351/89d77dc9-0e5f-4e11-bd1e-0c40fd16bd78)

SET logs the information in the xml file under /root/.set directory:
![image](https://github.com/sachinezhilmaran/creating-a-backdoor-with-SET/assets/128135351/a7c8256e-aca5-4f88-a9eb-fbe901e39741)

RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is examined successfully
