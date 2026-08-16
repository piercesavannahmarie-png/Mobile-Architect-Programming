# CS 360 Mobile Architecture and Programming

## MyWeightJourney Mobile Application

### Project Overview

For this course, I developed **MyWeightJourney**, a mobile weight-tracking application designed to give users a simple way to record and monitor their weight over time. The primary goal of the application was to create a functional and user-friendly mobile experience that allows users to create an account, log in, enter weight information, set a goal weight, and manage previously recorded entries. The application was designed around the need for a straightforward way to keep weight information organized without making the interface overly complicated.

### User-Centered UI Design

Several screens and features were necessary to support the needs of the user. The application includes login and account functionality, a main weight-tracking interface, weight entry management, goal weight functionality, and optional SMS notifications. Users can add new weight entries as well as edit or delete existing entries.

When designing the UI, I focused on keeping the application simple and easy to navigate. Information and controls were organized so that the most important features were easy to locate. I also tried to maintain a consistent appearance throughout the application so users would understand how to interact with each screen. These choices helped create a design that was functional while still keeping the user's experience in mind.

### Coding Approach

I approached the coding process by developing the application in smaller sections rather than attempting to implement every feature at once. I first made sure the basic interface and navigation worked and then added functionality such as account management, database storage, weight entries, goal weight, and SMS permissions. After implementing each feature, I tested it before continuing to the next part of the application.

Breaking the project into smaller tasks made it easier to identify problems and understand which part of the code needed to be corrected. This is a strategy I can continue using in future projects because it makes larger development projects easier to manage and reduces the difficulty of troubleshooting.

### Testing and Functionality

I tested the application throughout development using the Android emulator. I tested creating and logging into an account, adding weight entries, editing entries, deleting entries, setting a goal weight, and logging out and back in to verify that saved information remained available. I also tested the application's SMS permission behavior by both allowing and denying permission. The rest of the application continued to function correctly when SMS permission was denied.

Testing was an important part of the development process because a feature appearing correctly in the interface did not necessarily mean that the underlying functionality worked correctly. Testing revealed issues that needed to be corrected during development and helped verify that the final application behaved as expected.

### Innovation and Challenges

One of the biggest challenges during the development process was connecting the original UI design to actual application functionality. The interface created earlier in the course provided the visual foundation, but Project Three required turning those screens into a working application. I had to determine how the different Java classes, XML layouts, database functionality, permissions, and application navigation worked together.

I overcame these challenges by implementing and testing features individually. This allowed me to make adjustments without disrupting functionality that was already working. The process helped me better understand how the visual and functional components of an Android application work together.

### Areas of Success

I was particularly successful with the application's weight-entry management and data persistence. Users can add, edit, and delete weight entries, and the application retains the saved information after logging out and logging back in. This demonstrates my understanding of connecting a mobile user interface to stored application data rather than creating only a visual prototype.

I was also successful in implementing optional SMS functionality in a way that does not prevent the rest of the application from working if the user denies permission. This demonstrates the importance of considering user permissions and ensuring that optional functionality does not interfere with the application's primary purpose.

## Portfolio Artifacts

This repository includes the completed Project Three application code as a ZIP file, along with the app launch plan developed for the project. The completed application demonstrates my ability to apply mobile development practices, database management, user-centered UI design, permissions, testing, and Android application development. The launch plan complements the application by outlining considerations for releasing and maintaining the app, including its intended audience, platform requirements, monetization strategy, and future development opportunities.

## AI Acknowledgment

I used ChatGPT as a learning and support tool during portions of this project and reflection. It was used to help me better understand assignment requirements, troubleshoot development issues, explain Android development concepts, and assist with organizing and revising written content. I personally implemented, tested, reviewed, and finalized the application code and written work submitted for this course.
