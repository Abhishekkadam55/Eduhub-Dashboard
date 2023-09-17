# Eduhub-Dashboard

Case Study for Dashboard Creation:
Eduhub is an ed-tech startup that creates educational videos for students. The management 
wants to track whether the project is on track or not. Every video pass through three stages.

Stage 1: Script
Stage 2: Storyboard
Stage 3: Shoot
You have given a dataset that consists of data about various stages of a video.
Description of Features:
Subjects: Subject of Video
Script Key: Unique key for a video
Grade: Grade for which video is to be created
Video Release Month: Month in which the video will be released.
Script Due Date: Excepted Date of Script completion
Actual Script Closed: Actual Date of Script Completion.
Storyboard Due Date: Excepted Date of Storyboard Completion.
Actual Storyboard Closed: Actual Date of Storyboard Completion
Shoot Due Date: Excepted Date of Shoot completion.
Actual Shoot Closed: Actual Date of Shoot Completion.
If a particular stage is completed, then (Actual Date is there) then a “Completion Status” 
Tag must be given for that stage.
Description of Tag: Completion Status
Stage is completed before or on Due Date On-Time
Stage is completed within 5 days after the due date Delayed
Stage is completed more than 5 days after the due date Critically Delayed
Problem statement:
Create a Visualization in Power BI that fulfill the following requirements:
1. Tracks count of On Time, Delayed and Critically Delayed for every stage.
2. Visualization must have the following filters: Subjects, Video Release Month, Grade
