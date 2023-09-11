# Lab2 report

### Problems
There were no particular technical problems installing and using JPA.

### Link to code
https://github.com/WilliamWintersto/dat250-jpa-tutorial

### Questions

Where is the database? Explain the used database and how/when it runs.
- The database is in the top package "dat250-jpa-tutorial" with the name "DB.mv.db.". The database is configured in the persistence.xml file.
On line 10 we can see that the driver class is H2, which is a relational database management system. It is an embedded database that is initialized trough the entity manager.
The database is created on line 17 in CreditCardsMain.java. "entitymanager.gettransaction().begin()" initiates a new database transaction.

Can you provide the SQl used to create the table Customer (Hint: Hibernate is used for the object-relational-mapping)?
Answer: blablabla

Find a way to inspect the database tables being created and attach a screenshot of the database schema to your report. Do the created tables correspond to your initial thoughts regarding the exercise? (an explanation of how you inspected the database tables and what tables were created. For the latter, you may provide screenshots.)
Answer: aaaaaaa
        aaaaaaa

### Pending issues
As far as I know everything should be working now.
If not I must have misunderstood something.
