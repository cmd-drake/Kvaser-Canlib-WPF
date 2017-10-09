# Kvaser-Canlib-WPF

This project takes the Kvaser Canlib Library for C# Example Project, and places the DLL and driver all in one spot. 

To correctly run this example from Kvaser do the following:

1.) Install the driver executable for windows, found in the Prerequisites/Driver folder

2.) When first opening the project, point the canlibCLSNET.dll missing under references to the DLL under Prerequisites/DLLs

It should compile. 

This code sample from Kvaser is also modified to work better in maximized mode. 

Future works: 

I plan to also implement an Analyzer screen to show changes in the Canbus by CAN ID. 