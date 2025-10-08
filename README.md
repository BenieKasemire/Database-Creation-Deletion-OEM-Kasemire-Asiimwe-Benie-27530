# Assignment II: Database Creation, Deletion & OEM

Name: Kasemire Asiimwe Benie


ID: 27530

---

## Overview

This assignment centers on carrying out key database administration operations in Oracle, such as creating and removing Pluggable Databases (PDBs) and setting up Oracle Enterprise Manager (OEM). It showcases the ability to configure, manage, and monitor databases using OEM tools.

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



#### After navigating to this following OEM for signing in Username used is SYSTEM and Password used is BENIE




  ![Alt Text](https://github.com/BenieKasemire/Database-Creation-Deletion-OEM-Kasemire-Asiimwe-Benie-27530/blob/2514deeca5797cd38d179b4b3ad21f6b9244511c/screenshot7/task%203%20%20a.jpg)


  ![Alt Text](https://github.com/BenieKasemire/Database-Creation-Deletion-OEM-Kasemire-Asiimwe-Benie-27530/blob/5c688e12ad4b2d8c70c031d54aa97fe6861813a1/screenshot7/task3.png) 


  ![Alt Text]( https://github.com/BenieKasemire/Database-Creation-Deletion-OEM-Kasemire-Asiimwe-Benie-27530/blob/5c688e12ad4b2d8c70c031d54aa97fe6861813a1/screenshot7/task3(2).png) 



## Connecting to sqldeveloper

   ![Alt Text]( https://github.com/BenieKasemire/Database-Creation-Deletion-OEM-Kasemire-Asiimwe-Benie-27530/blob/5c688e12ad4b2d8c70c031d54aa97fe6861813a1/screenshot7/Screenshot%202025-10-08%20061753.png) 


  ![Alt Text]( https://github.com/BenieKasemire/Database-Creation-Deletion-OEM-Kasemire-Asiimwe-Benie-27530/blob/5c688e12ad4b2d8c70c031d54aa97fe6861813a1/screenshot7/Screenshot%202025-10-08%20061939.png)


---

## Notes & Challenges

Notes & Challenges

Throughout the assignment, several challenges were faced:

Issue connecting to the Container Database (CDB) during PDB creation.
Resolution: Verified SYSDBA privileges and confirmed correct directory paths in the FILE_NAME_CONVERT clause.

Delays in launching Oracle Enterprise Manager (OEM).
Resolution: Restarted the Oracle listener and confirmed that the Oracle Management Service (OMS) was active.

All problems were successfully resolved, allowing smooth completion of the tasks.

## Conclusion

This assignment offered practical experience in creating, deleting, and managing Oracle databases using OEM. It enhanced understanding of multitenant database architecture and reinforced essential administrative skills applicable in real-world database management scenarios.
