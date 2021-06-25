

This project provides a technical design and provision of a new database server and the development of a new database for LetsGetFit gym 
to store the details of the members, trainers, program. The boundaries of this project include setting up the relational database model 
to record the members personal details, their designed program plan, setting up their membership card in order to login into the gym. The 
enrollment setup is made in order to bring the members into desired plan that is available to them. The diet and program are designed 
exclusively for the members and recorded in the database.  The trainers set up the program plan and assign to the members. The progress 
chart database is made in order to develop the members progress in the gym. The brief view of the payment details to store the payment 
made by their members.

The assumptions that were made to design this database model are as follows:

•	If customer chooses a plan, he/she will not be allowed to change the plan until its fully completed.
•	A separate HR system that employs the trainers is not part to the database model. 
•	There is a separate system that handles the member payments and salary of trainers.
•	Members that checked GDPR option are retained on the system in a dormant state after membership expires.
•	The hard delete removes the personal details alone, but the business-related information is kept on record and hard delete is done manually through the stored procedure.
