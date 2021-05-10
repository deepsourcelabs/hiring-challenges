# Back-end Engineering Challenge

* **Timebox:** 3 hours
* **Technologies:** Python, Django, SQLite
* **Tests:** Nice to have
* **Documentation:** Nice to have

Pick one of these challenges to get started. Good luck! ✨

## Challenge #1: Password Manager

Keeping strong passwords on the services that you use on the Internet is important. It is also important to not re-use passwords across different services. Religiously doing these two things can save you from a lot of pain when any of the services that you use get compromised unfortunately. Your job is to build a password manager, called **TwoPassword**, that helps users generate and store passwords for the different services they use.

### User Stories

Feature | Description
------- | -----------
**User Management** | A new user should be able to sign up from the home page with their email address. The password that the users set during sign up will be treated as the Master Password. There should be an option to sign out and sign in as well.
**Dashboard** | Once a user has been authenticated, they should see their home dashboard that lists all the passwords they have created. They should be able to create a new password, delete an existing password, and search for a password using the website address. The list of passwords should be paginated.
**Password Management** | The user should be able to create a new password for a web service. Each password should contain at least the following properties: *website name*, *website address*, *password*. When creating a new password, the user can either add a custom password, or automatically generate a password from the UI.
**Password Access** | When the user is viewing an existing password, they should be asked for the Master Password before the stored password is revealed to them.

**Note:** This is a back-end focused challenge, so you can put minimal effort on the UI — but make sure the application is usable.
