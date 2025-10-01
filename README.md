# ADEloan - "ADEs" in managing your finances and loans.

## Authors
- Aiyanna Alaon
- Emma De La Cruz


## Problem statement
I'm sure everyone's gone through the stress of managing all our expenses, even for students like us, who are aware of economic challenges. You need to achieve any goals in terms of savings, keep track of people borrowing your cash in the digital world? This program is aimed to keep track of all these small and minor inconveniences with simple inputs.

Sure, there are other ways for 1 to record their expenses , like in a notebook, but what happens if it were to get lost? This project will be programmed to be accesible on your choice of device. 

## Problem objectives
1. Keeping records of the history of finances
2. Organize your goals (Trying to save up to a certain amount)

## Planned features
1. Checks whether you're under your saving goals, by tracking the amount of time left until the due.
2. Inputs of your recent purchases like receipts
3. Inputs receipts of recent loans to others
4. Wishlist (of some sorts)
 
## Planned inputs (All text entries)
(Inputs)
- Savings goals
   - Due date
- Recent purchases
- Items you want to be added to your wishlist
- Recents loans 
   - Asks if you loaned it to someone, or someone loaned it to you
   - Due
   - The Amount
(Outputs)
- Progress over time for your savings goals
- Reminds you when a due date for a loan or goal is near
- Comments on savings habits (not sure about this)

## Logic plan / Pseudocode
START PROGRAM

Enter current balance:

Display Menu :
  1 - Add a goal
  2 - Enter recent purchase
  3 - Enter recent loan

  IF user chooses 1
    ASK for (due date)
    ASK for (amount)
    ASK to go *BACK TO MENU* or *END SESSION*
  
  ELSE IF user chooses 2
    ASK for (item name)
    ASK for (date of purchase)
    ASK for (amount of the purchase)
    DEDUCT (amount of the purchase) from *current balance*
    ASK to go *BACK TO MENU* or *END SESSION*
  ELSE IF user chooses 3 
    ASK for (amount of the loan)
    ASK for (due date)
    ASK whether *received* *or sent*
    ASK for (name or category of the loan)
    DEDUCT IF *SENT* or ADD IF *RECEIVED*
    ASK to go *BACK TO MENU* or *END SESSION*

  END PROGRAM
  
