[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/S59Jpvw8)
# MIT App Inventor Project

# Community Connect

## Project Overview

Community Connect is a simple MIT App Inventor app created for the DGL 104 MIT App Inventor project. The purpose of the app is to help newcomers learn about respectful community engagement and encourage participation in positive social welfare initiatives.

The app focuses on creating a simple and easy-to-use experience while demonstrating software development concepts covered in DGL 104, including:

* app design
* documentation
* debugging
* refactoring
* testing
* organization of code blocks
* DRY programming principles

This project also demonstrates the use of storage components through TinyDB.

---

# Project Theme

The theme of this assignment is ethical and socially impactful app development connected to helping newcomers learn about the community and engage respectfully.

Instead of trying to represent the K’ómoks First Nation directly, this app focuses on encouraging users to:

* learn respectfully
* use official resources
* participate positively in community initiatives
* think about meaningful ways to contribute

I wanted to keep the app simple while still matching the assignment theme and demonstrating the programming concepts from class.

---

# Features

The app includes:

* Multiple screens for navigation
* Educational information about respectful community engagement
* A section where users can select ways they may want to get involved
* A text input area where users can save a personal action idea
* TinyDB storage for saving and loading notes
* Navigation buttons between screens
* Alert messages using Notifier
* Organized block structure
* Clearly named identifiers and components

---

# Screens

## HomeScreen

The HomeScreen introduces the app and allows the user to navigate to the other screens.

Features:

* Welcome message
* Navigation buttons
* Simple layout

Buttons:

* Learn About the Community
* Find Ways to Help
* My Saved Notes

---

## LearnScreen

The LearnScreen gives users a short introduction to respectful community engagement.

The screen encourages users to:

* learn from official resources
* attend public events respectfully
* support local initiatives
* understand the importance of listening and learning

---

## ActionScreen

The ActionScreen allows users to:

* choose possible community actions
* write a personal action idea
* save their note using TinyDB storage

The screen includes:

* CheckBoxes
* TextBox
* Save button
* TinyDB
* Notifier alerts

The save button checks whether the textbox is empty before saving.

---

## SavedScreen

The SavedScreen allows users to:

* load their saved note
* clear their saved note
* view stored information

TinyDB is used to retrieve and remove saved data.

---

# Components Used

The app uses the following MIT App Inventor components:

| Component           | Purpose                    |
| ------------------- | -------------------------- |
| Label               | Display text               |
| Button              | Navigation and actions     |
| CheckBox            | User choices               |
| TextBox             | User input                 |
| TinyDB              | Local storage              |
| Notifier            | Alert messages             |
| VerticalArrangement | Screen layout organization |

---

# Advanced Component Category

This project uses the **Storage** category through the TinyDB component.

TinyDB allows the app to:

* save user notes
* load saved notes later
* clear saved data

This helped satisfy the assignment requirement for advanced MIT App Inventor components.

---

# Development Process

I started by planning the app screens and deciding how users would move between them. I wanted the app to stay simple and easy to understand while still connecting clearly to the assignment theme.

The first thing I built was the HomeScreen. After navigation was working, I created the LearnScreen, ActionScreen, and SavedScreen.

Once the screens were connected properly, I added TinyDB storage so users could save a personal action idea and load it later.

During development, I focused on:

* clear naming conventions
* organized blocks
* reducing repeated code
* keeping the layout clean
* making navigation easy to follow

As I worked on the project, I started understanding why organization and readability matter so much in software development. It became much easier to debug the app when components and blocks were clearly organized.

---

# Refactoring and DRY Principles

One important concept from DGL 104 was DRY (“Don’t Repeat Yourself”).

To reduce repeated logic, I used:

* procedures for repeated actions
* clear component naming
* organized block sections

For example, navigation logic and alert messages were grouped together instead of repeating unnecessary blocks across multiple areas.

I also tried to keep the blocks editor clean and readable because large unorganized block structures quickly become difficult to debug.

---

# Naming Conventions

I used descriptive names for all major components.

Examples:

* `Button_SaveActions`
* `TextBox_UserNote`
* `Button_BackHome`
* `Label_SavedResult`

Using proper naming conventions made the blocks easier to read and helped connect components to their functions more clearly.

---

# Testing

I tested the app multiple times throughout development.

The testing process included:

1. checking screen navigation
2. testing TinyDB storage
3. testing saved note loading
4. testing note clearing
5. testing button functionality
6. testing empty textbox warnings

One important test was making sure the app would not save an empty note. If the textbox is empty, the app now shows an alert asking the user to write an action idea first.

Testing helped me understand how small bugs can appear even in simple applications and why testing is an important part of development.

---

# Code Review Summary

The project was reviewed by another student.

The review focused on:

* navigation
* layout
* usability
* component naming
* block organization
* TinyDB functionality

The feedback suggested improving some labels to make the instructions clearer for users. I also double-checked all navigation buttons after the review to make sure every screen returned properly.

This process helped me understand why code review is useful in collaborative software development.

---

# Challenges

One challenge during development was organizing the blocks cleanly as the app became larger. At first, some blocks became difficult to follow because they were spread around the workspace.

Another challenge was understanding how TinyDB stores and retrieves values. After testing and debugging several times, I was able to get the save and load functionality working correctly.

I also learned that naming components properly makes debugging much easier later.

---

# Future Improvements

If I continued developing this app, I would like to add:

* links to official community resources
* maps for community locations
* event calendars
* multiple saved notes
* better visual styling
* images and icons
* accessibility improvements

---

# Resources

## MIT App Inventor

https://appinventor.mit.edu/

## DGL 104 Course Materials

Course lecture materials from Weeks 1–6 were used for guidance on:

* debugging
* refactoring
* testing
* documentation
* GitHub workflow
* software organization

## K’ómoks First Nation

https://komoks.ca/

---

# References

Blacquiere, A., & Sarkar, D. P. (2026). *DGL 104 Lecture Materials*. North Island College.

MIT App Inventor Documentation. https://appinventor.mit.edu/

Fowler, M. (2018). *Refactoring: Improving the Design of Existing Code* (2nd ed.). Addison-Wesley.

Martin, R. C. (2008). *Clean Code: A Handbook of Agile Software Craftsmanship*. Prentice Hall.
