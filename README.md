# Medicine Shop Automation Software by CodeCannibals
## Software Engineering Project IIT Kharagpur

## About the software


The Medicine Shop Automation Software’s purpose is to automate Medicine Shop management and ease the shop owner’s workload. It is a convenient and easy-to-use application for the shop owner who has to deal with managing the medicine shop’s inventories and undergo various types of procedures involving transactions with vendors of the medicines and customers who buy the medicines. The system is based on a relational database with its Medicine Inventory and Transaction Records. It can handle efficient storage of data and provides the user with various functionalities. Above all, the software aims to provide a comfortable user experience to the medicine shop owners.


## Pre-requisites
Python 3.8.5  
Django 3.1.7  
Newer versions might have problem with the code.  
To install django  
```bash
pip install django==3.1.7
```


### For testing : 


In order to test the code, you need to install the coverage package. A simple command as below should work or you may go to the link for further installation instructions.



```bash
pip install coverage
```
## How to use
- `git clone https://github.com/Abhi-Kmr2046/MedicineShopAutomation.git`
- `cd MedicineShopAutomation/msa`
- `python manage.py runserver`

This will start a local server. Open the link in a browser. 

#### Username : admin
#### Password : hello

If password doesn't work create a new superuser.
### [Optional] Create new user:
 
```bash
python manage.py createsuperuser
```
You will be asked to enter your username, email, and password. Please do so in order to create a super user successfully. After that run the command below and proceed with the new login details.

```bash
python manage.py runserver
```

## Usage

The software is completely self-explanatory.

## Testing

Go to the msa directory.

```bash
cd /MedicineShopAutomation/msa
```
In this directory, run the following commands in order to automatedly test the software.

The below command runs all the test cases.

```bash
coverage run manage.py test
```
The below command gives the coverage report.

```bash
coverage report
```
The below command generates an index.html that can be opened in the browser which gives a detailed report of all the tests performed.

The index.html file is provided along with the software. This file is generated on our side.

```bash
coverage html
```

The above command also generates such a file. It is located in 
```bash
msa/htmlcov/index.html
```
