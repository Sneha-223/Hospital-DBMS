# Hospital DBMS

#### **Sneha Raghava Raju**

This is a  Hospital DBMS group project that was implemented in four phases: 

-  **Phase 1** - Defining the mini-world and listing the database requirements and the functional requirements.
- **Phase 2** - Use the requirements defined to draw out an ER diagram.
- **Phase 3** - Convert the ER Diagram to a relational model and then normalize (1st, 2nd and 3rd normal forms).
- **Phase 4** - Set up the hospital database in SQL and create a CLI using Python.

<br>

### Instructions to run Phase 4

run `mysql` and then enter the command `USE HOSPITAL` to use the hospital database.

Then run `python3 phase4.py` to run the CLI.


### Queries that can be performed on the HOSPITAL database:

**1. View details**
The details of several tables namely, Patients, Doctors, Appointments, Departments, Nurses, Services and Staff can be obtained using this query after the user chooses the name of the table.

**2. Searching for details of a patient of a particular birth year**
This query allows the user to input a birth year and outputs the patient details for the patients borm in that year.

**3. Display the total cost for items required in the inventory.**
This query outputs the total amount of money that would be required to buy all the items needed in the inventory.  This is calculated by doing PRICE * COUNT_NEEDED for each entry and summing it across entries. 

**4. Insert details**
This query allows the user to add a new row of details to the table required. The user can choose among patients, doctors and appointments here.

**5. Delete details**
This query allows the user to delete a row of details in the table required using its primary key (ID). The user can choose among patients, doctors, nurses and appointments here. The cascading effect has been taken care of.

**6. Updating salary details for the staff**
This query allows the user to update the salary of a member of the hospital staff i.e. any among the doctors, nurses and staff.

**7. Update the details of a patient**
This query allows the user to update the details of a particular patient accessed using the patient ID.

**8. Number of doctors and nurses in a department**
This query outputs the total number of nurses and doctors for the department that the user wants (inputted using department ID).

**9. Display patient details**
This query acts as a projection to give the user the details of all patients in the database.

**10. Display doctors with a certain specialisation**
This query provides a list of all doctors corresponding to the specialization given by the user.

**11. Logout**

