# ADEloan - "ADEs" in managing your finances and loans.

## Authors
- Aiyanna Alaon
- Emma De La Cruz


## Problem statement
In today's world, managing finances can be a significant source of stress, particularly for students navigating economic uncertainties. The need to save towards goals and track personal loans often goes unaddressed in our digital lives. This application aims to simplify financial management by providing a user-friendly platform to record expenses, track loans, and set savings goals.

While alternative methods for expense tracking exist, such as notebooks, the risk of data loss through physical damage or misplacement remains a concern. This project is designed to be device-accessible, ensuring data security and accessibility.

## Problem objectives
1. Keeping records of the history of finances
2. Organize your goals (Trying to save up to a certain amount)

## Planned features
1. Checks whether you're under your saving goals, by tracking the amount of time left until the due.
2. Inputs of your recent purchases, like receipts
3. Input receipts of recent loans to others
4. Wishlist (of some sort)
 
## Planned inputs (All text entries)
(Inputs)
- Savings goals
   - Due date
- Recent purchases
- Items you want to be added to your wishlist
- Recent loans 
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
  
