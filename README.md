# SoftwareDev2  - Room Access System - by Alex Roche

To access a user guide pdf doccument, which goes into detail of how to use the system and each of it's features, please click [here](https://drive.google.com/file/d/1w5vrnJqdsqj_4xUblRKBl_zK7Lc2TfAX/view?usp=sharing) 

When you start up the applictaion, you will be prompted to enter in some login credetails. These credentials are: Username = Admin, Password = abc. Any other credentials will not work and if they are incorrect, you will be prompted to enter them in again until you get the credentials correct. 

Once you have entered in the credentials, you will be prompted with a menu which allows you to access features by entering in a matching number displayed alongside the feature name. 

When entering in any command or a piece of information, after you have entered in the information, you MUST use the 'enter' key afterwards to carry out the process, otherwise an incorrect process may be carried out.  

DO NOT enter in a word where a number is required as this could break the system. If this happend when choosing a feature, then enter '10' to exit out of the system. If this happens when choosing a user role or a room type using the number system provided on the screen, then you will have to locate the entry from the project files and you will have to remove the entry manually, but make sure to save the file afterwards. 

Within the project there are two files, one listed as 'ID_Card_List' and the othr listed as 'map'. DO NOT touch the 'temp' file as this is a temporary file used to save changes made to the 'ID_Card_List' file and then copy changes back into the 'ID_Card_List'. 

The 'map' file stores all room names and their details.  

If you use the 'Barcode scanner simulation' feature, everytime a user attempts to access a room, an appropiate entry wil be made to a log file called 'room_access_log_{current date}' which will append entries if it has been used more than once during the day or it will create a new log file with the current date and the first barcode entry. 

To exit the program when the menu is loaded up, enter in '10' and the program will stop. If you wish to exit during a process, like adding user for instance, then please close down the screen. 


