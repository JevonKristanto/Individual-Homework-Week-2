C111118153 羅享福

# Work Breakdown Structure List 
| Task | Description |Time Required (Days) | Prerequisite tasks |
| ---- | ----------- | ------------------- | ------------------ |
| 1 | Develop Plans | 1 | - |
| 2 | Task Allocation | 4 | 1 |
| 3 | Get Hardware | 17 | 1 |
| 4 | Program Development | 70 | 2 |
| 5 | Install Hardware | 10 | 3 |
| 6 | Program Test | 30 | 4 |
| 7 | Writing a User Manual | 25 | 5 |
| 8 | Convert File | 20 | 5 |
| 9 | System Test | 25 | 6 |
| 10 | User Trainning | 20 | 7,8 |
| 11 | User Testing | 25 | 9,10 |

# Gantt Chart
```mermaid
gantt
 title A Gantt Diagram

 section section
 Research plan   : a1, 2024-10-03, 7d
 Task allocation : a2, after a1, 4d
 Find the paper  : a3, after a2, 7d
 Discussion content : a4,after a2,3d
 Analysis project   : a5,after a3 a4,10d
 Writing project    : a6,after a5,14d
 Discuss with professor : a7,after a3,20d
 Modify project     : a8,after a6,14d
 Design questionnaire : a12, after a7, 4d
 Distribute questionnaire: a9,after a7 a8,14d
 Analysis Questionnaire  : a10,after a9,4d
 Completed project       : a11,after a10,5d
 Submit project          : after a11,4d
```

# PERT/CPM Chart
```mermaid
graph TD;
A1(Task 1: Development plan Start date: 2024/10/01 End date: 2024/10/01 Duration: 1 day) --> A2(Task 2: Task allocation Start date: 2024/10/02 End date: 2024/10/05 Duration: 4 days)
A1 --> A3(Task 3: Obtain Hardware Start Date: 2024/10/06 End Date: 2024/10/22 Duration: 17 days)
A2 --> A4(Task 4: Program Development Start Date: 2024/10/06 End Date: 2024/12/14 Duration: 70 days)
A3 --> A5(Task 5: Install hardware Start date: 2024/10/23 End date: 2024/11/01 Duration: 10 days)
A4 --> A6(Task 6: Program Test Start Date: 2024/12/15 End Date: 2025/01/13 Duration: 30 days)
A5 --> A7(Task 7: Write user manual Start date: 2024/11/02 End date: 2024/11/26 Duration: 25 days)
A5 --> A8(Task 8: Convert File Start Date: 2024/11/02 End Date: 2024/11/21 Duration: 20 days)
A6 --> A9(Task 9: System Test Start Date: 2025/01/14 End Date: 2025/02/07 Duration: 25 days)
A7 --> A10(Task 10: User training Start date: 2024/11/27 End date: 2024/12/16 Duration: 20 days)
A8 --> A10
A9 --> A11(Task 11: User Test Start Date: 2025/02/08 End Date: 2025/03/04 Duration: 25 days)
A10 --> A11

```

# Critical Path Diagram
```mermaid
graph TD;
 A1[Research Plan] --> A2[Task Assignment];
 A1 --> A3[Get hardware];
 A2 --> A4[Program Development];
 A3 --> A5[Install hardware];
 A4 --> A6[Program Test];
 A5 --> A7[Write user manual];
 A5 --> A8[conversion file];
 A6 --> A9[system test];
 A7 --> A10[User training];
 A8 --> A10;
 A9 --> A11[User Test];
 A10 --> A11;

 style A1 fill:#f9f,stroke:#333,stroke-width:2px;
 style A2 fill:#f9f,stroke:#333,stroke-width:2px;
 style A4 fill:#f9f,stroke:#333,stroke-width:2px;
 style A6 fill:#f9f,stroke:#333,stroke-width:2px;
 style A9 fill:#f9f,stroke:#333,stroke-width:2px;
 style A11 fill:#f9f,stroke:#333,stroke-width:2px;
