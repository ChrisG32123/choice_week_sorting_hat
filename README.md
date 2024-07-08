# Choice Week Sorting Hat

At the end of a long and stressful semester, Choice Week is a program run by Tessellations School with two goals in mind:
1. Provide teachers time to frantically write report cards before the week is up
2. Pull a quick switcharoo on students so that they can be entertained for a week while teachers wrap up report cards

With these goals in mind, Choice Week can be described as a week of AM and PM sessions of activities put on by subsets of teachers. For example, a teacher could be slated for the Monday and Tuesday sessions (4 total) for taking students rock climbing then having Wednesday-Friday off for report card writing. Sounds like a great idea!

There's just one problem --logistics. There is simply not enough space for every student to get to do their favorite activity every session. Some activities are only meant for certian age groups. Some students don't work well together. How do we allocate the students to the activities in the most 'fair' way possible. Well...

This program is meant to solve this allocation and optimization problem. We simply need to collect a list of students and their attirbutes (students.csv), activities and their attirbutes (activities.csv), and finally conflicts (conflicts.csv and group_conflicts.csv). Then we run an optimizer over the constrained space and voila: Choice Week Student Allocation.

Obviously, there are more nuances to cover like the availability of sessions per activity, but for now we simply opt to create simulated data (simulate_data.ipynb) and create a proof of concept of the program's feasibility for automating the logistics of Choice Week (choice_week_allocation.ipynb).
