# <pre>                  IT314 - Software Engineering - Lab 1 </pre>

#### Name       : Aayush Brahmbhatt
#### StudentID  : 202001238
#### Date       : 03-02-2023

----
## Objective:
    Identifying Functional and Non-Functional Requirements

----
## 1. Identify FRs and NFRs
### Functional Requirements
 
    1. Employee and Student Login (User Login)
        - Checking out a book, returning a book, and extending the return date if no further reservations are made for that specific book
        - Mark a book if it has already been checked out by another person. 
        - A user must log in before they can borrow or return a book.

    2. Library Staff Login (Staff Login)   
        - View pending borrow requests that must be completed 
        - View the list of pending return requests
        - Retrieve the list of books that are currently accessible in the library
        - Viewing the daily transactions that are done for analysing library reach
        - Finding a book's placement on a shelf by browsing or searching the platform

    3. Librarian Login (Admin Login)
            - Create a new record to reflect the borrow of a book.
            - Delete the record of the borrowed book.

    4. Visitors who are not members should be free to browse the books.

    5. User privacy should be upheld with regard to the book(s) they are borrowing.

    6. The final web application should be able to handle concurrent login (or register) requests from both users and employees.

    7. The system should email enrolled students a reminder when the due date for a book return is approaching.

    8. The student or employee may view every book that was on the library's shelves. Additionally, the user should be able to quickly find the book that they need, and there should be search button
    
### Non-Functional Requirements
    
    1. Authentication - The user login must be authorised and validated by the system before returning the book.

    2. Scalability - The system must be able to accommodate a large number of users because it will be used by both employees and researchers.

    3. Reliability
        - The database must be kept current so that it doesn't show a book as available when it isn't (borrowed but not returned) or show a book as marked as borrowed by a user when that user already has the book
        - This will ensure that the user can only borrow books that are currently available and that they can only be returned if they had borrowed it.


    4. Maintainability 
        - The web application should have the capability of modifications and updates so that the technology used does not get outdated too quickly
        - It can be easily updated even if the developer team of the website changes after the deployment of final product
    
    5. Compatibility - The website should be simple to visit with any fundamental web browser that supports HTML5, as well as being able to function on a mobile device.

    6. Usability - The website's user interface (UI) needs to be straightforward but elegant so that any sort of user may simply search for books and carry out other tasks without any specific training. Voice assistant and language selection options can aid in barrier-free access.

    7. Accuracy - Data regarding the books and the assessed fines must be recorded accurately, consistently, and reliably.

    8. User credentials should never be disclosed in a data breach since privacy is at risk.

----
## 2. Identify scope, features and non-functional aspects of the following problem.

### 1. Scope
    - The application's target audience will be the 5% of the world's population who are suffering from hearing loss. 
    - This app would be targeting such people as they are the ones for whom the app is being designed for.
    - Optimizing the application to low latency than can be used for real time application.
    
### 2. Features
    - Low latency to enable real-time use
    - Alerts to user about the incoming sounds
    - The sounds recorded must also be logged properly in readable format
    - The App should alert the users when it recognizes the sounds of critical situations.
    - When a critical emergency is recognised and there is no reaction from the user, notify friends and family.
    - The app should run in the background also.

### 3. Non-Functional aspects
    - The App should alert the user through some vibrations.
    - When travelling, the app should be able to recommend the lanes with the least amount of traffic.
    - Users should be able to send their current position to friends and relatives in case of an emergency via the app.
    - Users should be able to add extra sounds, which the app must be able to identify the user.
    - The latency of the app should be at most 2 seconds.
    
----


