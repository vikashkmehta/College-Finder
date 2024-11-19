COLLEGE FINDER
COLLEGE FINDER is a database-driven project designed to store and retrieve detailed information about various colleges. This system includes college data such as campus area, eligibility criteria, placement ratios, fee structure, and scholarship details.

Features
College Information: Store details about college name, campus area, city, state, and campus life.
Eligibility: Criteria for admission based on exam rank, age, and class 12 marks.
Placements: Placement ratios, companies visiting the college, and highest placement packages.
Fee Structure: Semester fee, hostel fees, extra charges, and total fee.
Scholarships: Details of available scholarships, eligibility, and income-based discounts.
Database Tables
University
Stores general details about the university.

UID (Primary Key)
Uname (College Name)
State, City, Campusarea, etc.
Eligibility
Stores admission eligibility details for each university.

UID (Foreign Key)
xyz_ExamRank, Age, Class12thMarks
Placement
Stores placement-related information for each university.

UID (Foreign Key)
PlacementRatio, TopCompany, HighestPackage, etc.
Fee Structure
Stores fee details for each university.

UID (Foreign Key)
SemesterFee, HostelFee, TotalFee
Scholarship
Stores information about scholarships available at each university.

UID (Foreign Key)
Availability, WithinStateScholarship, xyz_examrank

ER Diagram 
![image](https://github.com/user-attachments/assets/f57256a1-b86c-4fda-a087-67951742890c)
