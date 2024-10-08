# Bus Scheduler App

This folder contains the source code for the Bus Scheduler app codelab.

# Introduction

The Bus Scheduler app displays a list of bus stops and arrival times. Tapping a bus stop on the first screen will display a list of all arrival times for that particular stop.

The bus stops are stored in a Room database. Schedule items are represented by the `Schedule` class and queries on the data table are made by the `ScheduleDao` class. The app includes a view model to access the `ScheduleDao` and format data to be display in a list, using `Flow` to send data to a recycler view adapter.

![image](https://github.com/user-attachments/assets/be0b2170-44a1-4009-a43d-94ae110b3b8c)
![image](https://github.com/user-attachments/assets/161f813c-600f-412d-98d4-c75cf52b466c)
