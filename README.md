# Project 1: Interactive Wheeled Robot Application

## Timeline

Activity                   | Deadline
-------------------------- | --------------------------------
Project Idea:              | Thursday, January 25th by 9:30am
Project Walkthrough and Review: | Tuesday, February 6th during lab
Engagement Materials:       | Thursday, February 8th by 9:30am
Final Submission:          | Tuesday, February 13th by 3pm   

## Class Community Guidelines

Throughout the completion of this project you must adhere to the [course guidelines](https://github.com/CMPSC-304-Robotic-Agents-Spring-2024/course_information). To report any violations of the code of conduct, please submit an [anonymous form](https://forms.gle/krHqgn4ycHMkAjPU8). Students who think that the class should revise some aspect of the guidelines must use the GitHub issue tracker for the [course information](https://github.com/CMPSC-304-Robotic-Agents-Spring-2024/course_information) repository to suggest, discuss, and implement any required changes.

By working on and completing this assignment you agree to use the hardware given to you in a responsible manner. Each team is responsible for the safety and security of the robot while it is in your possession. You are allowed to take the robot used in this project outside of ALIC but you have to return all parts at the completion of this project.

## Introduction

This project assignment invites you to work in a team of two to design and implement a robotic application using `gopigo` to be used for community demonstrations. Teams are also responsible for writing a detailed report, stored in the file `writing/report.md`. This is a Markdown file that must adhere to the standards described in the [Markdown Syntax Guide](https://guides.github.com/features/mastering-markdown/).

## Learning Outcomes

These assignment learning outcomes contribute to the following course learning outcomes described in the [course syllabus](https://github.com/CMPSC-304-Robotic-Agents-Spring-2024/course_information):

1. Identify components of the robot and associate each part with its task in a complete robotic system.
2. Design, implement, and test robotic applications for a wheeled, arm, and aerial robots.
5. Describe the ethical and social impact of robotics on public problems and participate in civic engagement activities with robots, while additionally reflecting on the nuances of public problems.

## Instructions

### Starting with the robot

- First, begin charging the battery, located in the little brown box.
- Then, you can connect to the robot by following instructions for [pairing gopigo](https://gopigo.io/pairing-gopigo-os/).

  **Note:** When you are done using GoPiGo, turn off the robot first. Then, after the robot has shut down completely, turn off the rechargeable battery pack. If you turn off the battery before the robot, you run the risk of corrupting the microSD card.

### Robot Design and Development for Community Demonstrations

Robotics has been identified and used as strong avenue to promote students' problem solving skills, and to introduce programming concepts and computational thinking skills.

Each team will select a task for the robot to complete and then design and implement a `gopigo` robot to complete that task. This project will be showcased during the community events this semester. Since there are no specific requirements or guidelines for this portion of the project, to ensure fairness in the amount of work you dedicate to this project, each team's selected task (what your robot will do) has to be approved by the instructor. In general, each team either needs to propose a unique robot design (e.g., the need to enhance the robot) and a solution for a simple task OR a simple design (e.g., minimal need for robot restructuring) with a solution for a more complex task (e.g., involving multiple sensors). You can explore [project ideas at the gopigo](https://gopigo.io/projects/).

Additionally, since this part of the project will be used as an educational resource to get our local community (think, families with K-6 students) excited about computing, each team needs to develop concrete motivation for the educational purposes of your robotic design and development. Article on [Educational Robotics and Robot Creativity: An Interdisciplinary Dialogue](https://www.frontiersin.org/articles/10.3389/frobt.2021.662030/full) will give you some background into robotics used for education. Specifically, your project should have the following  components related to community engagement:

- Three learning objectives for the proposed demonstration that are connected to computational thinking and/or problem solving. You must include at least one reference to motivate your chosen learning outcomes (research article, similar existing initiative, etc.).
- A hands-on component, which will either allow participants to experiment with the robot or observe varying performance of the robot under various scenarios.
- A sign/flyer for your project to be displayed at your station during community event.
- Supplemental engagement materials, as needed. 

You are required to submit your idea proposal by the due date in an appropriate subsection of the `report.md`'s "Planning for Robot Design for Community Demonstrations" section. Your team also needs to identify a timeline for completing this portion of the lab and include it in the table in the report. If you are in need of additional supplies that you could not find in ALIC, you need to include the list of supplies in the appropriate subsection of the report as well. Instructor will review proposed project ideas and notify you of approval or alternate suggestions within 24 hours.

### Summary of Baseline Deliverab;es

- Python program(s) implementing application using `gopigo` robot. GitHub flow must be followed, which includes working in branches, creating Pull Requests, and merging completed and approved work.
- Completed `report.md`.
- A flyer to display at your engagement station.
- Supplemental engagement materials.
- Peer review of at least one other project.
- Participation in the walkthrough.

### Resources

- [EasyGoPiGo3 Documentation](https://gopigo3.readthedocs.io/en/master/api-basic/easygopigo3.html#)
- [Sample `gopigo` programs](https://github.com/DexterInd/GoPiGo_Python_Examples/blob/master/Sample_Programs_GoPiGo3)
- [`pygame.mixer` library](https://www.pygame.org/docs/ref/mixer.html)

  Sample code for using the speaker:
```
import pygame

# Play music
pygame.mixer.init()    
pygame.mixer.music.load("music.mp3")
pygame.mixer.music.play()
```

## Project Walkthrough and Review

### Project Walkthrough

During the lab session on Thursday, February 6th, each team will participate in the project walk-through process. Project walkthrough is an informal process where the instructor facilitates the process of reviewing the progress of the project and the written code. The purpose of this walkthrough is to motivate continuous progression on the project, identification of any conceptual issues, and detection of any technical errors. When the walkthrough is finished, the authors of the project are responsible for taking the necessary actions to correct the identified issues.

By this project walkthrough, each team should have mostly finished the implementation of their intended solution. During the walkthrough, the team members will collaboratively lead the walkthrough process with a TL/instructor, which should last 5-10 minutes for each team. Each team should:

- Describe the chosen task.
- Explain and demonstrate the written code.
- Identify the steps left to complete for this project.

### Peer Review

Each person must peer review implemented work of another team. All teams must submit a Pull Request with their completed work up to this point before February 6th. You will receive peer review assignments before the lab session on February 6th. You must follow GitHub Flow practices to conduct a review, which includes a written review.

## Assignment Assessment

The grade that a student receives on this assignment will have the following components.

- **GitHub Actions CI Build Status [up to 10%]**: For project1 repository associated with this assignment students will receive a checkmark grade if their last before-the-deadline build passes.

- **Peer Review [up to 5%]**: Each person will receive a part of their grade for peer reviewing another team's project. Peer reviews are not to be done by a whole team but individually. 

- **Mastery of Verbal Explanation during Walkthrough and Demonstration [up to 15%]**: Since the continuous and timely project development and the ability to communicate technical details of a project is crucial to building successful software and hardware applications, a portion of students' lab grade will be determined based on the quality of the project walkthrough and the project demonstration.

- **Mastery of Technical Writing [up to 15%]**: Students will also receive a checkmark grade when the responses to the writing questions presented in the `report.md` reveal a proficiency of both writing skills and technical knowledge. To receive a checkmark grade, the submitted writing should have correct spelling, grammar, and punctuation in addition to following the rules of Markdown and providing conceptually and technically accurate answers.

- **Mastery of Technical Knowledge and Skills [up to 50%]**: Students will receive a portion of their assignment grade when their project implementation reveals that they have mastered all of the technical knowledge and skills developed during the completion of this project. All programs must be inside `src/` directory. As a part of this grade, the instructor will assess aspects of the project including, but not limited to, the correctness of the program, the completeness and correctness of the software and hardware integration, the use of effective source code comments and Git commit messages.

All grades for this project will be reported through a student's gradebook GitHub repository (to be set up soon).

## GatorGrade

You can check the baseline writing and commit requirements of this project by running department's assignment checking `gatorgrade` tool To use `gatorgrade`, you first need to make sure you have Python installed. If not, please see:

- [Setting Up Python on Windows](https://realpython.com/lessons/python-windows-setup/)
- [Python 3 Installation and Setup Guide](https://realpython.com/installing-python/)
- [How to Install Python 3 and Set Up a Local Programming Environment on Windows 10](https://www.digitalocean.com/community/tutorials/how-to-install-python-3-and-set-up-a-local-programming-environment-on-windows-10)

Then, you need to install `gatorgrade`:

- First, [install `pipx`](https://pypa.github.io/pipx/installation/)
- Then, install `gatorgrade` with `pipx install gatorgrade`

Finally, you can run `gatorgrade`:

`gatorgrade --config config/gatorgrade.yml`

## Assistance

If you are having trouble completing any part of this project, then please talk with the course instructor during the laboratory session. Alternatively, you may ask questions in the Discord channel for this course. Finally, you can schedule a meeting during the course instructor's office hours.
