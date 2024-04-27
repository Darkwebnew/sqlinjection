# sqlinjection
Exploiting SQL Injection vulnerability

# AIM:
To exploit SQL Injection vulnerability using Multidae web application in Metasploitable2

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode


### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
SQL Injection is a sort of infusion assault that makes it conceivable to execute malicious SQL statements. These statements control a database server behind a web application. Assailants can utilize SQL Injection vulnerabilities to sidestep application safety efforts. They can circumvent authentication and authorization of a page or web application and recover the content of the whole SQL database. 

Identify IP address using ifconfig in Metasploitable2

![WhatsApp Image 2024-04-23 at 09 18 25_ec1704e7](https://github.com/Darkwebnew/sqlinjection/assets/143114486/2c2b4a86-e6f7-4a98-b6ec-2c9faf406e37)

Use the above ip address to access the apache webserver of Metasploitable2 from kali linux. In Kali Linux use the ip address in a web browser.

![image](https://github.com/Darkwebnew/sqlinjection/assets/143114486/4c8abdb8-4735-4cac-8f15-4236eee3dac3)

Select Multidae from the menu listed as shown above. You will get the page as displayed below:

![image](https://github.com/Darkwebnew/sqlinjection/assets/143114486/6e8dbd04-1af0-4274-98c2-ebef406f3f2e)

Click on the menu Login/Register and register for an account

![image](https://github.com/Darkwebnew/sqlinjection/assets/143114486/7b6f5ebe-75b8-4237-b213-ff2726da6054)

Click on the link “Please register here”

![image](https://github.com/Darkwebnew/sqlinjection/assets/143114486/c57558b6-27b6-417a-afee-06192d88fdf3)

Click on “Create Account” to display the following page:


## RESULT:
The SQL Injection vulnerability is successfully exploited using the Multidae web application in Metasploitable2.
