# Cplusplus_Diary_Management

Started: November 29, 2023

Description: Management System that you input in a simple manner. An entry (or Record) has the date that it was entered (mm/dd/yyyy), the time it was entered (hh:mm), name of the person putting in the entry, the article says to put in a location and duration, but I am not sure if that is the direction I wish to go or if I want to give something
else that may be more relevant, and finally a note. The article also has the View, Edit, and Delete Record functions password protected and where you can change the password. 

Some things that I might change:
  - No password, not sure how to do passwords yet so it might be a future funciton, but not at the start.
  - I'll probably keep the location and duration, but I want to figure out a more relevant, at least for me, information that I wish to store. Maybe I'll create a diary system that works more for what I do, like a time management program.

Starting Steps:
  - Create the initial functions: Add Record, View Record, Edit Record, Delete Record
  - Use a Structure to store arrays to hold the different values for each record (Structure{addRecord[], viewRecord[], editRecord[], deleteRecord[]})
  - Have a Menu() function to give the user a menu for what they wish to do
  - Start with the Add Record function
