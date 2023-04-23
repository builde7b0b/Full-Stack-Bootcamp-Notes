



schema.sql
Relational Models 
https://git.generalassemb.ly/java-interapt-3-13-2023/databases/tree/master/sql-relational-mapping-lesson

ACID Transitions 
https://git.generalassemb.ly/java-interapt-3-13-2023/databases/tree/master/acid-transactions




## SCENARIO ONE: 
With which ACID principle(s) is the scenario dealing? Isolation, atomicity, consistency
Assuming the DB is ACID compliant, what should happen? The brother should get 6 and I should get 4 since there only 10 left.
What would happen if the DB was not ACID compliant? What could go wrong in this transaction? Due to Atomicity, the entire transaction will fail if the DB is NOT ACID compliant.

## SCENARIO TWO: 
Durability
The tranasaction was successful, just crashed due to traffic.
The transaction failed although the confirmation was sent to the customer.

## SCENARIO THREE: 
Durability
although the DB is compliant, we need to add new toner cartridge to continue the transaction.
If the DB was not compliant, the transaction would fail without printing pages.

## What are the steps?
sign into banking app
view balances 
withdraw 1,000 from checking account

## How does ACID come into play during the transaction?
We need atomicity when withdrawing funds and reading balances to ensure that every part of the transaction succeeds.
Durability will allow us to confirm that the withdrawal was complete with a confirmation message.
Isolation means that transactions can occur independently without interference from other transactions.
Consistency keeps the data accurate between transactions such as updating the new balance after we withdrawn funds