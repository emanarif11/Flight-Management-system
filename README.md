# Flight-Management-system
1. Introduction

The Flight Management System (FMS) is a console-based airline reservation program built using C++ and fundamental Data Structures & Algorithms.
It allows users to:

Book seats

Cancel seats

View seat map

Search flights

Handle waiting list using Queue

The focus is on DSA implementation, not GUI.

2. Objectives

Apply Arrays, Queues, and optionally Linked Lists

Understand real-world airline reservation logic

Practice OOP using classes

Implement waiting list logic

Manage dynamic seat allocation

3. System Architecture

The system consists of:

✓ Flight Class

Stores seat data, status, and waiting list.

✓ Passenger Class

Stores passenger details (optional).

✓ System Class

Handles overall user interaction.

4. Features
✔ Seat Booking

Automatically assigns next available seat.
If full → adds user to waiting list.

✔ Cancellation

Frees seat.
If waiting list has someone → assigns freed seat.

✔ Waiting List

Implemented using Queue (FIFO).
Ensures fairness.

✔ Search Flight

Displays flight, seating, status.

✔ Seat Map

Grid view showing O = Available, X = Booked.

<img width="202" height="322" alt="image" src="https://github.com/user-attachments/assets/6f014b72-b545-43c5-a28c-6919d37e2717" />    <img width="209" height="309" alt="image" src="https://github.com/user-attachments/assets/e2255de2-2bc3-4cf1-9116-2b1e08a3623c" />

 <img width="179" height="236" alt="image" src="https://github.com/user-attachments/assets/a9df4dec-29a1-4e06-8a29-536195b894c5" />





