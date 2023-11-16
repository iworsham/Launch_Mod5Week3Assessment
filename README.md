# JeffersonCountyLibrary

## Setup
* Fork and Clone this repository
* Run `update-database`

## Exercise (12 points)

Check out a new branch and complete the following tasks **in order**:
* 2 points - There is a bug in our authentication!  Identity looks like it is set up, but we can't register users.  Find and fix this bug! (Hint: this should only take one line of code)
* 2 points - Right now, anyone can 'check out' a book.  Update the application so that only a logged in user can check out a book.
* 4 points - In this application, we have the ability to create new books.  Improve this functionality by:
  * Add a link from the nav-bar to add a book
  * Make sure only Librarians can add a book
* 2 points - Create a descriptive pull request and merge this branch into main
* 2 points - Take a screenshot of a database query result from pgAdmin that clearly shows which users in your database are librarians.  Update this README to include your screenshot below:

  < YOUR SCREENSHOT SHOULD GO HE![image](https://github.com/iworsham/Launch_Mod5Week3Assessment/assets/35874300/a768d115-1c62-45b0-9741-698ea0c66ab0)
RE >

  

## Questions (6 points)

Answer the questions below in this README.  Answer these questions as if you are in an interview!

1. What are roles and claims as they relate to Authentication and Authorization?
Roles are users who all share the same privledges in a application for example, a web app may have a 'Admin' role where a they have all the privledges the app can offer without any restrictions. Claims are statements about a users identity. Claims are based on personal information, so instead of having certain access based on your role, claims can be based on email or race. For example, most websites ask for age verification, users can have access based on their age depending on the claim policy.

3. How do cookies play a role in authentication and authorization?
   Cookies play a major role in authentication and authorization by saving user data on a website. Whenever you log into an website that is authentication. For example you ever log into instagram on your laptop and you are already signed into your account without having to log any credentials. Thats because whenever you first logged into instagram, instagrams servers generated a cookie that saved your user session ID onto your laptop and your session remains active however long you have that cookie is stored. Now you do have the option to disable cookies in the event you logged on a device that wasn't your personal, like most libraries and schools do. Authorization is a little different that cookie is still stored and saves your session ID but now it checks your permissions based on the session information to see what you are "authorized" to do and allow you to see what you are "authorized" to see. A good example would be zoom, zoom saves a your session ID onto a cookie on your device so that everytime you click that link you are logged in and ready to go. But you aren't session host. Session Hosts are allowed permissions and certain authorizations to be able to create breakout rooms, allow other users to record, and if need be they can kick another user out of the zoom call.

4. If asked to implement Auth in a new .NET application, would you use the Identity framework?
   Yes, I would use Identity framework to implement auth in my .NET application. Its a good framework for managing user accounts, login features, and controlling who does what. Its reliable and easy to use because it is used by lots of other developers, and there's enough documentation to understand it clearly. Another plus is that it's already built into .NET core.

## Rubric

This assessment has a total of 18 points.  Earning 12 or higher is a pass!
