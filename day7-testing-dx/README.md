### 1.  Why Testing Matters 
Testing matters in Salesforce because it helps make sure our code works correctly before it is used by real users. 
In Salesforce, developers write Apex classes, triggers, and automation to perform different tasks. 
If there are mistakes in the code, it can cause errors, wrong data updates, or system failures.

### 2. What is Asynchronous Apex?
Asynchronous Apex in Salesforce is a way of running code in the background without stopping the user’s work.
It is used when tasks take more time, like processing large data or making external API calls.
Instead of running immediately, the code is executed later in a separate process. 
This helps improve system performance and avoids timeouts. Common types include Future Methods, Batch Apex, Queueable Apex, and Scheduled Apex.
It makes applications faster and more efficient.
### 3.  What is Salesforce DX? 
Salesforce DX is a modern development tool used in Salesforce to make building and managing applications easier.
It helps developers work in a more organized and team-friendly way. With Salesforce DX, we can use version control (like Git) to track code changes.
It also allows creating and managing scratch orgs for testing new features safely. 
This improves collaboration, speed, and code quality. For students, it is a better way to practice real-world Salesforce development.
### 4. Complete System Workflow 
    ( End-to-end explanation) 
A complete system workflow in Salesforce explains how data and processes move from start to finish in a system. It begins when a user enters or updates data in the application. 
The request then goes through validation rules, triggers, and business logic written in Apex.
After processing, the data is stored in the database and may trigger workflows or automations like email alerts.
Finally, the result is shown back to the user or sent to other systems. 
This end-to-end flow ensures smooth, automated, and efficient business operations.
### 5. Important Test Cases 
    (Your examples)
  Important test cases in Salesforce are used to check whether the code works correctly in all  situations. 
  Example:
   >> we test if a record is created successfully when valid data is given. 
   >> We also test negative cases like missing required fields or invalid inputs.
   >> Another test case checks bulk operations, like inserting multiple records at once. 
   >> We should also test triggers to ensure they run correctly on insert, update, or delete.     
   >> Finally, we verify that expected errors or messages appear when rules are violated.
### 6. Reflection 
    Why enterprise software development needs structured workflows 
Enterprise software development in Salesforce needs structured workflows because many users and systems depend on it. 
Without a proper workflow, data can become inconsistent or incorrect.
Structured steps like validation, testing, and deployment ensure that changes are safe and reliable.
They also help teams work together without conflicts using version control and clear processes. 
This reduces bugs and improves system stability. Overall, structured workflows make the software more scalable, secure, and easy to maintain.

