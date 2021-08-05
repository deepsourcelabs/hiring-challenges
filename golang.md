# Go Developer Challenge

* **Timebox** 4 hours
* **Technologies** Golang
* **Tests:** Must have
* **Documentation:** Nice to have

Pick one of these challenges to get started.  Good luck! ✨

## Challenge #1: Password Manager CLI

Password managers have become an essential utility in day-to-day life.  However, as developers, using a browser is, at times, not an option.  Imagine you have ssh'd into a server and need to access credentials to your database.  Your job is to build a simple headless password manager that helps you access your credentials over a simple TCP link.

### User Stories

Feature | Desciption
------- | ----------
**TCP Based Protocol** | Users should be able to interact with your password manager over a simple TCP connection using a simple text based protocol.
**User Management** | A new user should be able to sign up with a master password using a `signup <password>` command.  The user should be able to login and logout of a session using simple commands.
**Password Management** | The user should be able to create, retrieve, update and delete passwords.  Each password can have a label associated with it.  Look above for an example of the command.

**Note:** This challenge is intended to test your ability to work with standard Go libraries and features.  Before submitting, ensure that you document your protocol (commands and responses).  We will test the service by using a telnet command.

**Example Command** 

Command:
`> create <label> <username>:<password>`
`created`

