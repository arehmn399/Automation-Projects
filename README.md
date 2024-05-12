	
In this zip file python script named main.py is the full and final code that you have to run in run in your computer.
In order to run it you have to first download some drivers and libraries in your system. The information of those drivers
will be provided by one of our engineer.

=>Additional Excel Files:

This zip file has two execel files named "followers.xlsx" and "private_accounts". 
Followers.xlsx will hold name of those followers to which we have already send the message.
Private_acct.xlsx will hold name of those followers which have private account or "Message" button isn't available.

=>Important Point:

Remember always empty both file whenever you are going to write new message.  However, if you're sending the same message again,
you don't need to clear any files. This ensures that if you need to stop the script while it's running, it will save the data 
of the followers to whom messages were sent in the "followers.xlsx" file. When you restart the script, it will continue 
sending messages from where it stopped.


=>In this readme.txt I am gonna inform you how to use your python script. 
In the script there are five places where you have to do changes based on your requirements.

1) Message:

In the script there is variable name "message" on which you have to write your custom message.

2) Main User_name:

In the script there is variable name "username_main" and "password_main". You have to write 
instagram details of that account from which you want to send custom messag to the followers.
In the given file that data is "jpqosshrg3" and "yb8K0Ef3wv" respectively. You have to alter
these positions.

3) Target User_name:

In the script there is variable name "target_username". You have to give user name of that account
whose followers you want fetch and send message.

4) Credential_list

In the script there is a list named "credential_list" right below the "target_username" variable. 
Here, you can provide instagram account details of multiple user. These are those people who login
to their instagram account, go the targeted username and fetch the list of followers. Fetching
of followers should be done from different individual account so that we could get different followers
each time. 
The length of the list is not fixed. You can provide any number of account in the credential_list.

5) chrome_driver_path:

You have to download a driver based on the current chrome version you are using. After downloading 
you have to provide the path where you download that particular driver. One of our engineer will
help you to download those drivers and libraries. 



Note:

This code only send message to those followers whose accounts are not private and has a "Message" button available
when you open there instagram ID.
