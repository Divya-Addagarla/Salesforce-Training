
## 1. What is Apex?
 Apex is the programming language used in Salesforce to write custom business logic and automate processes on the platform.

## 2. Difference: 
     Flow vs Apex 
     Configuration vs Coding
 - Flow vs Apex
      - Flow is used for  click-based (no coding) , Used for simple automation and Easier for implementing.
      - Apex is used for coding-based (programming language), Used for complex logic and More powerful and flexible.
- Configuration vs Coding
      - Configuration is used for  using clicks (setup tools) and it does not require programming language.  Faster and easier
      - Coding is done using Apex code , Used when clicks are not enough and More control and customization.

##  3.Real Examples Where Apex Is Needed 
    (3 examples)
  - Bulk Data Processing<br>
    When thousands of records need to be updated at once , Apex handles it efficiently.
  - Assign Case to Specific Team  <br>
    When a customer raises a complaint about “Technical Issue”, it should automatically go to the Technical Support team.
  - Email Alert After Special Condition
    When a customer places an order above ₹50000, the system should automatically send an email to      the manager for approval.

## 4.. Integrated System Design 
    Explain your complete College Management System using: 
           CRM 
           Objects 
           Relationships 
           Validation 
           Flow 
           Apex 
  -  CRM<br>
    We use CRM to manage all college data like students, courses, fees, attendance, and faculty in  one system.
  -  Objects
    We create  objects like:
      -Student
      -Course
      -Faculty
      -Enrollment
      -Fees
      -Attendance   
    Each object stores related data.
  -  Relationships
  We connect objects using relationships:
    Student --> Enrollment (Master-Detail / Lookup)
    Course --> Enrollment (Lookup)
    Faculty --> Course (Lookup)
  This helps link data properly.
  - Validation
  We use validation rules to avoid wrong data:
    Fee cannot be negative.
    Email must be valid format.
    Attendance cannot be more than 100%.
  This keeps data clean.
  -  Flow
  Flow is used for automation without code:
  When a student enrolls, automatically create enrollment record.
  Send email confirmation after admission.
  Auto-update fee status when payment is done.
  -  Apex
  Apex is used for complex logic:
  Calculate final grade based on multiple exams.
  Assign students to courses based on eligibility.
  Bulk update attendance for thousands of students.

## 5. Pseudocode Examples 
     (Add your logic examples) 
  - 1. Auto Create Enrollment Record<br>
      ''' WHEN a new Student is created
      THEN create an Enrollment record
      SET Student = current student
      SET Status = "Active" '''
  - 2. Fee Validation Rule<br>
     ''' IF Fee Amount < 0
      THEN show error "Fee cannot be negative"
      STOP record save'''
  - 3. Attendance Check<br>
    '''  FOR each Student
      IF Attendance < 75%
      THEN mark as "Low Attendance"
      SEND warning email to student '''

## 6. Reflection 
    Why enterprise systems eventually need programming 
  Enterprise systems like Salesforce need programming because click tools are not enough for complex business rules.
  They handle large data, so code is needed for fast processing
  They need to connect with other systems
  Every company needs custom features and programming is needed for advanced and complex requirements.



