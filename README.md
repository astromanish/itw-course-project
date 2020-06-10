
# VENUE BOOKING SYSTEM / HOTEL MANAGEMENT SYSTEM

# This project is an Tkinter based(Python Module) application that can be used by any hotel for room booking.
 
# This application is made as a project for ITW Course under Prof. L.P. Singh Sir

# Splash Screen
On first opening this application users are prompted with a splash screen showing a picture of Hotel and some text over it and then after a period of 3000 sec this prompt will automatically get closed and main menu screen will get opened.

# Main Menu Screen

Under main menu screen user will get lots of option to choose and by default Reserve option from navigation panel of main menu will opened after closing of splash screen.

On main menu screen , just below the top heading "HOTEL MANAGEMENT SYSTEM" user will get the navigation panel which contains lots of option to choose from.
Different options available on navigation panel are explained below.
 
1. Hotel Status

To check the total number of guests in the hotel now.
To find the total number of available and reserved rooms.

2. Rooms

To check the amenities available in the room.
To get the status of room (i.e. available or reserved).

3. Reserve

To Reserve a room.
A filter is also provided which gives you the option to fill fields(amenities) according to the guest's choice and find the available rooms with the choosen amenities sorted in order from lowest price to highest price.

4. Payments Info

To find the payment information by providing the payment id.
Payment id is generated numberwise from 1,2,3... and so on after each reservation.
# As database is already filled in withsome reservation details so it has reservation details upto payment id 32.
So one can check payment details of any payment id from 1 to 28 or if new reservation is made after 32 one can also check that. 

5. Contacts 

To find contacts of different authorities of hotel.

6. Exit

To close the application

## Content of Zip Folder

1. Readme.md

Contains all important details related to this project.

2. main.py

Application program itself.

3. hm_proj.db

Database of application program.
It already contains details of amenties of each room from 1 to 20 which one can check in Rooms section of main menu screen.
After a reservation is made it will save payment details with date,time and amount which one can check in payments info section of main menu screen.
Filter feature of reserve section of main menu screen also work by help of this database.

4. images

Contains all images for the application program.

5. ScreenShots

Contains screenshots of different instances of running application program.

## Requirements 

One need to have python-3 installed on his/her system to run this program.




