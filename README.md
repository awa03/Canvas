# Canvas
This project is an attempt to recreate the popular grading application Canvas.

# Why This Project is Closed Source
This project is currently closed source due to academic restrictions. This project will become open source in the near future. For now this repository will only hold the precompiled version of the project. A link will be provided when open source is avalible. 

# New Features

There were many new features in this update. This update marks the entry into the beta stage of development. Within this deployment, rest implementation has been partially implemented (Comming in Beta 1.0). Features in this release range from the addition of assignments to fully-fledged student and instructor functionality. 

This program offers a simulation, similar to a platform that houses millions of users, in which students and teachers can virtualize classroom grading! This allows for more accessible student data, as well as on-the-fly updates to students' grades. This program accomplishes this goal by utilizing the dotnet Maui framework. 

****

## Instructor
(<b>New</b>) Selected Instructor View - Within this view, the instructor is allowed the opportunity to create, edit, and delete their taught courses. The purpose of this view is to create a centralized location for the instructor's courses, as well as to provide an easy-to-find route for editing course information. 

(<b>New</b>) Selected Course Instructor View - Within this view: the instructor is allowed to add, edit. and delete students' assignments. When a student (from the student list) is selected their assignments are presented in a separate list view. On the selection of one of these assignments (or none in the case of assignment addition), the view navigates to the Selected Course View.

(<b>New</b>) Selected Course View - The selected course view (only accessible via instructors) allows for the addition of assignments (to the selected student or all students). The assignment contains the following data:
- Name
- Description
- Due Date
- Points /  Possible Points
- Submissions (<b>Only Read Functionality for Instructors</b>)

## Student

(<b>New</b>) Selected Student View - This view allows for the student to select and enter a course. Additionally, the student is provided a button to modify their enrollments.

(<b>New</b>) Enrollment Dialog - This view allows students to manage their enrollments. Students are provided with a list of classes available within their school. When a course is selected students have the option to enroll or unenroll from their selected course. Upon selecting the enrollment option the course will be promptly added to the student's course roster.

(<b>New</b>) Selected Course View - The selected course view, which is only accessible to students, allows for students to view their assignments and create a new submission. Upon selecting an assignment, and entering its view, students are prompted with a text entry box.

****

## Goals For Beta Release

- [ ] Grading needs to be improved upon (GPA calculator, Course Grade, etc.).
- [ ] Ui Improvements (Specifically in the instructor view)
- [ ] Finish RestAPI implementation (Finish Controller / DTO Implementations)
- [ ] Improve Course Structure

****

## Release Images

![AddAssignment](https://github.com/awa03/Canvas/assets/118379307/d296b15f-48e6-4e9c-81ca-f27923c4b9be)
![CanvasHome](https://github.com/awa03/Canvas/assets/118379307/099e3419-a4c1-482b-bf06-4c9f596e5e50)
![InstructorHome](https://github.com/awa03/Canvas/assets/118379307/e8fb7896-4029-4b98-af8c-d7ea206b633f)
![SelectedInstructor](https://github.com/awa03/Canvas/assets/118379307/68d65662-b2e0-45b6-98a1-37cc6922a729)
![StudentHome](https://github.com/awa03/Canvas/assets/118379307/f2d7c1a9-e8c8-4505-917f-e76b0277742b)
![StudentHome2](https://github.com/awa03/Canvas/assets/118379307/8fcce2d0-f398-4511-9fd1-58af9659ca1f)
