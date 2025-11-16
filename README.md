# Queue Management System (C++)

This project is a simple simulation of a **queue management system** such as bill payment queues or subscription queues.  
It is built using **Object-Oriented Programming (OOP)** in C++ and includes features such as:

- Issuing new tickets (`IssueTicket`)
- Displaying queue information (`PrintInfo`)
- Printing tickets Right-To-Left (`PrintTicketsLineRTL`)
- Printing tickets Left-To-Right (`PrintTicketsLineLTR`)
- Printing all tickets (`PrintAllTickets`)
- Serving the next client (`ServeNextClient`)

---

## 🧩 Project Components

- **clsQueueLine**: A class that represents a queue with a specific capacity and code.
- Functions to manage tickets (issue, print, serve).
- Demo usage creating two queues (PayBills & Subscriptions).

---

### Program Output
Subscriptions Queue Info:

                         _________________________

                                Queue Info
                         _________________________

                            Prefix   = B0
                            Total Tickets   = 3
                            Served Clients  = 0
                            Wating Clients  = 3
                         _________________________


                Tickets:  B01 <--  B02 <--  B03 <--

                Tickets:  B03 -->  B02 -->  B01 -->


                               ---Tickets---
                          _______________________

                                    B01

                            16/11/2025 - 13:20:2
                            Wating Clients = 0
                              Serve Time In
                               0 Minutes.
                          _______________________

                          _______________________

                                    B02

                            16/11/2025 - 13:20:2
                            Wating Clients = 1
                              Serve Time In
                               5 Minutes.
                          _______________________

                          _______________________

                                    B03

                            16/11/2025 - 13:20:2
                            Wating Clients = 2
                              Serve Time In
                               10 Minutes.
                          _______________________

Subscriptions Queue After Serving One client

                         _________________________

                                Queue Info
                         _________________________

                            Prefix   = B0
                            Total Tickets   = 3
                            Served Clients  = 1
                            Wating Clients  = 2
                         _________________________
