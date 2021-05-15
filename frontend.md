# Front-end Engineering Challenge

* **Timebox:** 3 hours
* **Technologies:** VueJS, Vuex, TypeScript, TailwindCSS
* **Tests:** Nice to have
* **Documentation:** Nice to have

Pick one of these challenges to get started. Good luck! ✨

## Challenge #1: API Helper

The Internet runs on APIs. When building a new web service, the chances are very high that you'd be integrating with a number of third-party services. Working with 3rd party APIs can often be clunky, so your job is to make it easy. You need to build a webapp, called **Postoffice**, that helps you interact with third party APIs easily.

### User Stories

Feature | Description
------- | -----------
**Make API requests** | The user should be able to make an API request to a 3rd party API from the UI. All known HTTP methods should be supported. The requests should also support sending HTTP headers and data in various formats if needed.
**View API response** | Once the API request returns, the user should be able to view the response in the UI in the correct format. If the response is a JSON, it should be properly formatted. If the response is an image, it should be displayed.
**History** | All API requests made should be added to the history. The user should be able to go to the history view and look at the old requests (and their responses).
**Persistence** | All the data needed for PostOffice to work should be persisted locally. So if the webapp is reloaded, the user should still see the same data and get back to the place that they left off from.

**Notes**:

* You can use [httpbin.org](https://httpbin.org/) to test our the APIs.
* Please feel free to use any other third-party library that you need to build the application.
