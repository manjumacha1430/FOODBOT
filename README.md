# Zephyr-Chatbot

Saffron Aroma Café Chatbot - Zephyr

Welcome to the Saffron Aroma Café Chatbot, Zephyr! Zephyr is a chatbot designed to enhance the user experience on the Saffron Aroma Café website by providing seamless order creation and order tracking functionalities. Here's a brief overview of Zephyr's capabilities:

Order Creation:
1.Zephyr allows users to create new orders directly through chat. Users can add items from the café's menu, specify quantities, and remove items if needed.
2.Zephyr is connected to a backend database that stores information about food items, including their names, prices, and available quantities.

Order Tracking:
Users can track the status of their orders by providing the order ID. Zephyr retrieves the order information from the backend database and displays the current status (e.g., in progress, in transit, completed).

Backend Database Integration:
Zephyr's functionality relies on a backend database that stores information about food items, orders, and their statuses. The database ensures seamless communication between the chatbot and the café's ordering system.

Total Price Calculation:
After finalizing the order, Zephyr calculates the total price based on the selected items and quantities. Users receive a summary of their order, including the total price and unique order ID for reference.

So how do you create this on your own, follow these steps:
1.First download the index.html file and the images (food1 to food20 are enough) that are in the repo.
2.Now you need to install two softwares, pycharm community edition and mysql workbench.Do download them from their respective websites and install them on your computer.
3.Now download the main.py, db_helper.py, generic_helper.py and chatbot.sql files.Open all the .py files with pycharm community edition. For opening the sql file you need to do a small procedure.
4.Open the Mysql workbench and create a new connection (if you dont know refer this https://youtu.be/Rm0xH2Vpfi0?si=THRPl_rimM9T2uLB upto 7:00 minutes) after this now in the options menu goto server->data import-->select import from self contained file and copy the downloaded sql file path from your computer and press start import.Then this step is over.
5.You need to do the chatbot training using the Dialogflow refer this video https://youtu.be/2e5pQqBvGco?si=pf5IPuRy03T_Gb7Y upto 1:05:00.
6.NOTE: 
https://youtu.be/2e5pQqBvGco?si=pf5IPuRy03T_Gb7Y
This whole chatbot is done with the help of this video, you can refer the video if you want to.Obviously you want to refer most parts of the video where you need to give weebhook connection on.
7. Let me tell you clearly , for sure you need to watch upto 1:05:00, sorry about that, and while developing backend you can keep pressing the forward 10seconds but until you see that he gives the webhook connection on for somer intents.
8. Then your chatbot is ready.
