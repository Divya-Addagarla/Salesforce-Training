##1. Difference Between: 
     #### App , Object  , Record  ,Field 
      = App	is a collection of related tabs, objects, and tools used for a business purpose.
            Ex  :  School Management System
      - Object is a database table that stores a type of information.
            Ex  :  Student Table
      - Record is a single row/data entry inside an object.
            Ex   :  One Student
      - Field	is a column/attribute that stores specific information in a record.
            Ex  :  Student Name, Roll No, Grade

##2. Standard vs Custom Objects 
   Standard Objects are already built in by Salesforce, like Account, Contact, and Lead, and are used for common business needs. Custom Objects are created by users when they want to store special or extra information that standard objects don’t cover, like Student or Project

##3. Your College Data Model 
  Include: 
        Objects 
        Relationships 
        Diagram/image
>> Objects
  we use the following objects:
      Student,Course,Enrollment,Professor,Department,Fees
>> Relationships
 A Student belongs to one Department
 A Department has many Students
 A Department has many Professors
 A Professor teaches many Courses
 A Student can enroll in many Courses
>> Diagram
 Department
   │
   ├──< Student >──┐
   │               │
   │               v
   ├──< Professor   Enrollment   >── Course
   │
   v
 Fees
##4. Formula Fields 
(Your examples + explanation)
   A formula field automatically calculates values using other fields. It updates itself whenever data changes.

Examples:
1. Full Name (Contact)
Combines first and last name:
     FirstName & " " & LastName
2. Age (from Birthdate)
Calculates age: 
     YEAR(TODAY()) - YEAR(Birthdate)
3. Account Name Display (Contact)
Shows related Account name:
   Account.Name
4. Status Message
   Shows Active or Inactive:
   IF(IsActive = TRUE, "Active", "Inactive")

##5. Validation Rules 
(Your examples + explanation) 
   A Validation Rule is like a “data check” that prevents wrong or incomplete information from being saved.
Examples
  1. Contact must have Email
    ISBLANK(Email)
    Error: Email is required before saving the contact.
  
  2. Age must be 18 or above
   Age__c < 18
   Error: User cannot enter age less than 18.
  
  3. Phone number must be 10 digits
    LEN(Phone) <> 10
     Error: Phone number must be exactly 10 digits.
  
  4. Contact must match Account ZIP Code
    AND(
    NOT(ISBLANK(AccountId)),
    MailingPostalCode <> Account.ShippingPostalCode
    )
    Error: Contact ZIP must match Account ZIP.

##6. Reflection , Why structured enterprise data matters
  structured data is important because it keeps information clean, organized, and easy to use. It helps users avoid mistakes, reduces duplicate data, and makes it easier to find and understand information. With structured data, businesses can work faster and make better decisions.
  





   
       
  
     
