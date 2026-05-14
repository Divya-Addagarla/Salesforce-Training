## 1.What is SOQL? 
   SOQL stands for Salesforce Object Query Language.SOQL is used  to get data from Salesforce records.It works similar to SQL, but it is specially made for Salesforce objects like Account,Contact,Opportunity,Lead.

##  2.What is an Apex Trigger? 
   An Apex Trigger in Salesforce is a code that runs automatically when something happens to records in Salesforce.It can run when records are:Created , Updated, Deleted, Restored.

## 3. Difference: 
     Flow vs Trigger 
     Before vs After Trigger 
- Flow vs Trigger 
Flow and Trigger are both used for automation in Salesforce.<br>
A Flow is a no-code tool where users can create automation using drag-and-drop options. It is easy to learn and mostly used for simple tasks. <br>
Apex Trigger is written using Apex code and runs automatically when records are created, updated, or deleted. Triggers are mainly used for complex business logic.
-Before vs After Trigger
Before Trigger runs before the record is saved in Salesforce. It is mainly used to update or validate field values before saving the record.<br>
After Trigger runs after the record is saved in the database. It is used when we need the record ID or when creating related records and performing other actions after saving.

## 4. Your Trigger Use Cases 
    (5 examples) 
- Automatically update a field value when a new record is created.
- Send a notification or email when an important record is updated.
- Prevent users from deleting important records.
- Create related records automatically after saving a record.
- Validate data before saving to ensure correct information is entered.

## 5. Query Examples 
    (Your English query ideas) 
- Show all Account names from Salesforce.
- Display all Contacts with first name and last name.
- Find all students whose city is Vijayawada.
- Show Opportunities with amount greater than 50,000.
- Display all Leads created today.


## 6. Reflection 
    Why enterprise systems react automatically to data changes 
Enterprise systems in Salesforce react automatically to data changes to save time, reduce manual work, and improve accuracy. Automatic actions help businesses update records, send notifications, validate data, and maintain consistency without human effort. This makes business processes faster, more reliable, and efficient.
