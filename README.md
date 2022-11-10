# VehicleRentalSystem

## Project Description:
  * “Vehicle Rental System” is a project which highlights the application of Object-Oriented Programming and helps us to understand how useful is the OOPs concepts in a programming language.
  * We got an opportunity to explore different libraries and modules available in python. We learnt connecting a DataBase to python with the help of “sqlite” module. Also, we learnt how to read data from an excel file and how to manage it which is done with the help of “openpyxl” module.
  * Tkinter is a very wonderful module in python which is used for making user friendly GUIs. Major chunk of programme for this project is of Tkinter to transform a raw programme which will be running in terminal only to a beautiful GUI which is equivalent to an application.

## Hardware Requirements:

No Hardware requirement

## Software Requirements:
  * Visual Studio Code (Code Editor):
  * Python Compiler
  * Microsoft Excel
  * GitHub

## Project Summary:
Our project is an online Vehicle Rental application where we give 4 different types of vehicles on rent to customers which includes
  1. **Bike**
  2. **Car**
  3. **Bicycle**
  4. **Scooter**

The complete program of this project is in Python language and we use Object-Oriented Programming approach to reduce complexity and number of lines in programme. Another major highlight in our project is GUI interface which we created with the help of Tkinter module in Python.

Following are some of the modules and libraries we used

  1. **<ins> Tkinter: </ins>**
      * Tkinter is the standard GUI library for Python. It provides a powerful object – oriented interface to the Tk GUI toolkit.
  
  2. **<ins> Python sqlite3: </ins>**
      * Python sqlite3 is an excellent module with which you can perform all possible DataBase operations within memory and persistent database in your applications.
      * In our project we connect a database file “Users.db” to Python with help of sqlite3 module.

  3. **<ins> random: </ins>**
      * It is a python module to generate random numbers.
      * In our project we used this module for generating reference number and receipt number.

  4. **<ins> datetime: </ins>**
      * This module supplies classes to work with current date and time.

  5. **<ins> openpyxl: </ins>**
      * It is a python module which is used to read data from an excel file or write to an excel file. A spreadsheet is represented as a workbook in openpyxl.

Programme for Vehicle Rental System is divided into 3 main classes. Those are as follows: 
  1. **user class:** Useful methods (functions) in this class are discussed below:
      *  login: - User enters username and password. If it matches with data in database, the user logins successfully. If not, throws error that username not found.
      *  new_user: - User can create account by setting new username and password and will then able to login.
      *  widgets: - This method packs the above two methods in beautiful GUI interface.

  2. **list class:** - Useful methods (functions) in this class are discussed below:
      * LOV: - Displays the list of all 4 types of vehicles i.e. Bike, Car, Bicycle, Scooter.
      * Bike/ Car/ Bicycle/ Scooter: - Displays all models of every Vehicle type by reading “Vehicle.xlsx” file using openpyxl module.
      * RAV: - Gives option to user to return a vehicle which he rented initially.
      * logout: - Gives option to user to logout and terminate the programme.
      * checkSrNo: - Gives option to user to enter serial number of vehicle model he rented. If it matches then allow user to proceed with payment else throws an     error.
   3. **ReturnVehicle Class:** - Useful methods (functions) in this class are discussed below:
      * Damage_chk: - Add damage cost to final bill amount if there is any damage in vehicle.
      * iExit: - Gives option to exit and terminate the programme.
      * Receiptt: - Creates buttons and entry widgets for getting user details.
      
   4. **afterselectingVehicle:** -
      * This class has programme for printing user details entered by user in entry widgets and print it in receipt.
      * For calculation of final bill amount to be paid by user.
      * Reset option to clear all details entered by user in entry widgets.
      * Back( ) method for going to back to window with “Return a Vehicle” option.

## Conclusion and Future Work:
  * ***Vehicle Rental System*** is a fully fledged programme written in Python language using Object - Oriented Programming concept designed with the help of Tkinter module which can be further used to design an app.

## References:
  * GitHub
  * Google
  * Python Documentation

    
    
    
    
      
