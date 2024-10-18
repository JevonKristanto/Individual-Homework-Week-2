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

#  PERT/CPM Chart 
'''mermaid

 A1 (Task 1: Development plan<br>Start date: 2024/10/01<br>End date: 2024/10/01<br>Duration: 1 day) --> A2 (Task 2: Task allocation<br> br>Start date: 2024/10/02<br>End date: 2024/10/05<br>Duration: 4 days)
 A1 --> A3 (Task 3: Obtain Hardware<br>Start Date: 2024/10/06<br>End Date: 2024/10/22<br>Duration: 17 days)
 A2 --> A4 (Task 4: Program Development<br>Start Date: 2024/10/06<br>End Date: 2024/12/14<br>Duration: 70 days)
 A3 --> A5 (Task 5: Install hardware<br>Start date: 2024/10/23<br>End date: 2024/11/01<br>Duration: 10 days)
 A4 --> A6 (Task 6: Program Test<br>Start Date: 2024/12/15<br>End Date: 2025/01/13<br>Duration: 30 days)
 A5 --> A7 (Task 7: Write user manual<br>Start date: 2024/11/02<br>End date: 2024/11/26<br>Duration: 25 days)
 A5 --> A8 (Task 8: Convert File<br>Start Date: 2024/11/02<br>End Date: 2024/11/21<br>Duration: 20 days)
 A6 --> A9 (Task 9: System Test<br>Start Date: 2025/01/14<br>End Date: 2025/02/07<br>Duration: 25 days)
 A7 --> A10 (Task 10: User training<br>Start date: 2024/11/27<br>End date: 2024/12/16<br>Duration: 20 days)
 A8 --> A10
 A9 --> A11 (Task 11: User Test<br>Start Date: 2025/02/08<br>End Date: 2025/03/04<br>Duration: 25 days)
 A10 --> A11
'''

