# University Application



## Project Description

The University Application is designed to facilitate the management of student data and course enrollment in a university setting. It allows students to register, log in, select and drop courses, and view their rankings within each course. The system ensures that course allocations are managed efficiently, including handling waitlists for full courses.

## Features

### Course Management
- **Read and store courses**: Load courses from files for each semester and store them in memory.
- **Update course files**: Reflect changes in available slots and waitlists in course files.

### Student Registration and Login
- **Student registration**: New students can register by providing their details.
- **Password validation**: Ensure that passwords meet strength requirements.
- **Student login**: Registered students can log in using their credentials.

### Course Selection
- **Select courses**: Students can select courses for their current semester.
- **Check availability and prerequisites**: Verify course availability and prerequisites before allocation.
- **Waitlist management**: Add students to a waitlist if the course is full.

### Course Allocation and Waitlist Management
- **Allocate courses**: Allocate courses to students based on availability.
- **Manage waitlists**: Automatically allocate courses to waitlisted students as slots become available.
- **Rank students**: Rank students within each course based on CGPA and number of projects and and participation in other clubs.

### Course Dropping
- **Drop courses**: Students can drop previously selected courses.
- **Update slots**: Increase available slots for other students when a course is dropped.
- **Allocate waitlisted students**: Assign waitlisted students to newly available slots.

### Rankings and Display
- **View rankings**: Students can view their rankings in their enrolled courses.
- **Ranking criteria**: Rankings are based on CGPA and number of projects and and participation in other clubs.

### File Management
- **Data storage**: Store and update course data, student data, and waitlists in respective files.
  - **Course files**: Contain details of each course, such as course ID, name, available slots, and enrolled students.
  - **Student files**: Store student information, including registration details, enrolled courses, CGPA, and project count.
  - **Waitlist files**: Maintain lists of students waiting to enroll in courses that are currently full.
  - **Rank files**: Store ranking information for students in each course based on CGPA and projects and participation in other clubs. 

- **File operations**: Read data files at startup and update them during program execution.
  - **Initialization**: Load courses, students, and waitlists from files into memory.
  - **Periodic updates**: Reflect changes such as course enrollments, drops, and waitlist updates in the respective files.




## To run the code

To run this project 

```bash
  gcc  filename.c
  ./a.out
```
# Acknowledgements

This project was developed as a part of [UCS2201-Fundamentals and Practice of Software Development] course offered by SSN Institutions
