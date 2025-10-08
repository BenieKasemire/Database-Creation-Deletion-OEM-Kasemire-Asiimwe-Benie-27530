# Assignment II: Database Creation, Deletion & OEM

Name: Kasemire Asiimwe Benie
ID: 27530

---

## Overview

This assignment focuses on performing essential database administration tasks in Oracle, including creating and deleting Pluggable Databases (PDBs) and configuring Oracle Enterprise Manager (OEM). The tasks demonstrate knowledge of database setup, management, and monitoring through OEM.

---

## Task 1: Create a New Pluggable Database (PDB)

A new Pluggable Database (PDB) was created using the following format:

- PDB Name: be_pdb_27530
- Username: benie_plsqlauca_27530  
- Password: BENIE 



![Alt Text](https://github.com/BenieKasemire/Database-Creation-Deletion-OEM-Kasemire-Asiimwe-Benie-27530/blob/5c688e12ad4b2d8c70c031d54aa97fe6861813a1/screenshot7/task1.png)






![Alt Text](https://github.com/BenieKasemire/Database-Creation-Deletion-OEM-Kasemire-Asiimwe-Benie-27530/blob/5c688e12ad4b2d8c70c031d54aa97fe6861813a1/screenshot7/task%201%20(2).png) 




 




---

## Task 2: Create and Delete a PDB

A second PDB was created and deleted as part of the exercise.

- PDB Name: be_to_delete_pdb_27530

After successful creation, this PDB was deleted to demonstrate database deletion commands and cleanup.


- PDB Creation

     ![Alt Text]( https://github.com/BenieKasemire/Database-Creation-Deletion-OEM-Kasemire-Asiimwe-Benie-27530/blob/5c688e12ad4b2d8c70c031d54aa97fe6861813a1/screenshot7/task%202.png)




- PDB Deletion

  
  ![Alt Text](https://github.com/BenieKasemire/Database-Creation-Deletion-OEM-Kasemire-Asiimwe-Benie-27530/blob/5c688e12ad4b2d8c70c031d54aa97fe6861813a1/screenshot7/task2(2).png)



---

## Task 3: Oracle Enterprise Manager (OEM) Configuration

Oracle Enterprise Manager (OEM) was configured successfully to monitor and manage the created PDBs.  
The OEM dashboard displays the database environment and user account information.



### After navigating to this following OEM for signing in Username used is SYSTEM and Password used is BENIE




  ![Alt Text]( https://github.com/GIULYINEZA2/Database-Creation-Deletion-OEM-Ndayishimiye-Ineza-Giuly-27390/blob/cef6ecb211db3d2fe288f3c58311886986bb3465/screenshots/Screenshot%202025-10-04%20134929.png) 


  ![Alt Text](https://github.com/BenieKasemire/Database-Creation-Deletion-OEM-Kasemire-Asiimwe-Benie-27530/blob/5c688e12ad4b2d8c70c031d54aa97fe6861813a1/screenshot7/task3.png) 


  ![Alt Text]( https://github.com/BenieKasemire/Database-Creation-Deletion-OEM-Kasemire-Asiimwe-Benie-27530/blob/5c688e12ad4b2d8c70c031d54aa97fe6861813a1/screenshot7/task3(2).png) 



## Connecting to sqldeveloper

   ![Alt Text]( https://github.com/BenieKasemire/Database-Creation-Deletion-OEM-Kasemire-Asiimwe-Benie-27530/blob/5c688e12ad4b2d8c70c031d54aa97fe6861813a1/screenshot7/Screenshot%202025-10-08%20061753.png) 


  ![Alt Text]( https://github.com/BenieKasemire/Database-Creation-Deletion-OEM-Kasemire-Asiimwe-Benie-27530/blob/5c688e12ad4b2d8c70c031d54aa97fe6861813a1/screenshot7/Screenshot%202025-10-08%20061939.png)


---

## Notes & Challenges

During the assignment, the following challenges were encountered:

- Difficulty connecting to the container database (CDB) while creating PDBs.  
  Solution: Ensured proper connection as SYSDBA and verified the paths used in the FILE_NAME_CONVERT clause.
  
- Delays in starting the Oracle Enterprise Manager service.  
  Solution: Restarted the Oracle listener and ensured the Oracle Management Service (OMS) was running.

All issues were resolved, and the tasks were completed successfully.

---

## Conclusion

The assignment provided hands-on experience with Oracle database creation, deletion, and management through OEM. It strengthened understanding of multitenant architecture and administrative operations essential for real-world database environments.
