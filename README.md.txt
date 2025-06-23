# SAP ABAP Leave Request Application

A custom SAP ABAP report for managing employee leave requests, featuring validations, custom table insertion, and dynamic selection screens.

Tech Stack:
- ABAP (SE38)
- Custom Transparent Table (`ZSA_LEAVE_REQUES`)
- HR Table: `PA0001`
- Dropdowns via `VRM_SET_VALUES`
- Custom Message Class (`ZMS_LEAVE_REQUEST`)

 Features:
- Employee number validation from `PA0001`
- Date range checks (From date <= To date)
- Required field validation
- Submit and Clear buttons on selection screen
- Data insertion into Z-table with status tracking

Z-Objects Used:

| Object Name              | Type                |
|--------------------------|-------------------- |
| `ZLEAVE_REQUEST_APP`     | Report Program      |
| `ZSA_LEAVE_REQUES`       | Transparent Table   |
| `ZMS_LEAVE_REQUEST`      | Message Class       |

 How to Use:
1. Clone or download the repository.
2. Upload the code to your SAP system.
3. Execute report `ZLEAVE_REQUEST_APP` from SE38.
4. Test using valid employee numbers and leave types.

 Contact:
SANKIRTHANA VINDYALA
GitHub: https://github.com/sankirthana123/sankirthana123  
