Project: naive-ticket-machine
Authors: David Barnes and Michael Kölling

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling
   Pearson Education

It is discussed in chapter 2.

Purpose of project: To illustrate the basics of fields, constructors, and methods.
How to start this project: Create one or more TicketMachine objects.

Questions and answers



Question 2.

After printing the ticket, the machine's balance is $0.


Question 3.

If you insert too much money into the machine, you do not recieve any refunds. -

The balance goes back to $0

If you do not insert enough money, it seems that it would still print the ticket.


Question 5.

The printed ticket from the second machine is really similar to the first one. The

only differences are the name of the machines and the price of their tickets.



Question 6.

Public class Student {

}



Public class LabClass {

}

Question 7.
The error message that I recieve says " class, interface, enum, or record 
expected". In my opinion, this does not explain well the problem, because it
doesn't state the problem in a complete english sentence. 

Question 8.
It is possible to compile without the word "public"

Question 9.
It is not possible to compile without the word "class"

Question 10. List of fields, constructor, methods
fields
private int price;
private int balance;
private int total;
Constructor
public TicketMachine(int cost)
    {
        price = cost;
        balance = 0;
        total = 0;
    }
Methods
 public int getPrice()
    {
        return price;
    }
 public int getBalance()
    {
        return balance;
    }
 public void insertMoney(int amount)
    {
        balance = balance + amount;
    }
public void printTicket()
    { ...
    }
    
Question 11.
It has the name of the class.
It has no return type.

Question 12. 
private int count; - Int
private Student representative; - string
private Server host; - string

Question 13. 
alive
Person tutor
Game game


















