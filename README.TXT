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

Question 14. 
Skipped

Question 17.
private int status;

Question 18.
Student

Question 19.
There are 2 parameters. A string and a double

Question 20. 
Yes, the values of the constructor's parameter will need to be stored somewhere 
persistant. In the "Book" class, it is likely to find integers integers and strings
,maybe even doubles or characters. The names of the fields are up for the programmer
to decide, so we can't know for sure. 

Question 21.
public Pet(String petsName) 
{ 
    Bob = petsName;
}

Question 22.
public Date(string month, string day, string year)

Question 23. 
The header and the body of the getBalance has the word Balance, while getPrice, has 
the word Price in its header/body.

Question 24. 
How much money is already in the machine?

Question 25.
No, the body doens't need to change its name for it to compile. 
It means that the accessor method and the field don't necessary have to match.
//but it could be confusing if they don't

Question 27.
It says "missing return statement".

Question 28. 
The main difference is that the getPrice and printTicket all mention a 
return type. Ex. void, int. However, the TicketMachine class doesn't have that.

Question 29. 
No they don't have return statements, I believe it's because they are constructors 
placed at the end. 

Question 31.

score = score + points;

return score;

Question 32. 
The addCredits method is a mutator, bexause it changes the value of the field, credit.

Question 33.
{
    price -= amount;     //or price = price - amount
}

Question 34. 
public void setAge(int currentAge){
   age = currentAge; 
    
}

Question 35.

private boolean setStatus (boolean alive){
    
}if //I don't know


Question 36.
When I inspect the price stays as $0.

Question 37.
My cat has green eyes.

Question 39.
Instead of giving out the value of price, it would print out the word "price"

Question 40.
It would print out the phrase "# price cents." every single time, no matter the price.

Question 42.
They show different outputs. They show the price of the object I called. So 
the ticketMachine priced at 10 cents would show me 10 cents, the 30 cents would show
30 cents.


Question 43. 
skipped it shows errors when I try to put System.out.printf(“# %d cents.%n”, price);


Question 44.
It no longer asks for a price when you construct a new ticketMachine. 

Question 46. 
The empty method is a mutator because it changes the data. Resets the total to 0.










































