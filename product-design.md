# Product Design Challenge

As part of your submission, answer some questions and create a high-fidelity mockup for a design challenge using Figma. If you are also able to show low-fidely mocks that illustrate your thought-process better, it'll earn you brownie points. Good luck! ✨

## Questions

1. What is your favorite product in terms of design? What do you like and what don’t you like? How would you improve it?

2. Assume you are paired with a front-end engineer. You are assigned with revamping the primary marketing [landing page](https://deepsource.io). Explain, in as much detail as possible, your design process from ideation to actually shipping the new version.

3. Which of your personal design works are you the most proud of? Explain your design philosophy behind it and why you think it's your best work. Also add public links to it.

4. DeepSource is a tool for developers. How would you go about doing user research? Explain your process in detail.

5. What is the newest thing you’ve learned that has improved your design work? Why did you decide to invest time in it? How did you apply it afterward?

## Challenge #1: Password Manager

Keeping strong passwords on the services that you use on the Internet is important. It is also important to not re-use passwords across different services. Religiously doing these two things can save you from a lot of pain when any of the services that you use get compromised unfortunately. Your job is to design a password manager, called **TwoPassword**, that helps users generate and store passwords for the different services they use.

### User Stories

Feature | Description
------- | -----------
**User Management** | A new user should be able to sign up from the home page with their email address. The password that the users set during sign up will be treated as the Master Password. There should be an option to sign out and sign in as well.
**Dashboard** | Once a user has been authenticated, they should see their home dashboard that lists all the passwords they have created. They should be able to create a new password, delete an existing password, and search for a password using the website address. The list of passwords should be paginated.
**Password Management** | The user should be able to create a new password for a web service. Each password should contain at least the following properties: *website name*, *website address*, *password*. When creating a new password, the user can either add a custom password, or automatically generate a password from the UI.
**Password Access** | When the user is viewing an existing password, they should be asked for the Master Password before the stored password is revealed to them.
