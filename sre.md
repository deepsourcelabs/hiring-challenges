# SRE Hiring Challenge
As an SRE, you are expected to be comfortable with all parts of the development lifecycle.  For this challenge, you are to build a simple app and deploy it on Kubernetes.  (You can use Minikube to deploy)
## Development
The application you have to write is a simple Todo list application with just the APIs.  You can use any language of your choice to write this service.  The service will follow these APIs.
### POST /todos
***Request:***
```json
{
	"title":"Title of your task",
	"description":"A description of your task.",
	"priority":"High/Medium/Low",
	"due_date":"2022-01-23 13:01:03"
}
```
***Response:***
```json
{
	"id":"h8324h-3942uj9f-4t9u34-83g4h-9u4f9u",
	"title":"Title of your task",
	"description":"A description of your task.",
	"priority":"High/Medium/Low",
	"due_date":"2022-01-23 13:01:03"
}
```

### GET /todos
```json
[
	{
		"id":"h8324h-3942uj9f-4t9u34-83g4h-9u4f9u",
		"title":"Title of your task",
		"description":"A description of your task.",
		"priority":"High/Medium/Low",
		"due_date":"2022-01-23 13:01:03"
	},
	{
		"id":"uh5fh-6tf9f-vugh38-dsv4-9eg3f9u",
		"title":"Title of your task",
		"description":"A description of your task.",
		"priority":"High/Medium/Low",
		"due_date":"2022-01-23 13:01:03"
	}
]
```
  
## Infrastructure Requirements
- Use MySQL/Postgres to store data.  
- We would like this app to run inside a K8s cluster.  Only the app you have written should be accessible outside the cluster.  The databases, or any other infrastructure components should not be accessible outside the cluster.
- Make sure your app can autoscale if the CPU usage goes above 50%.
- Make sure your tests are automatically run for every pull request.

## Notes
- Your primary goal should be to get the app live inside a K8s cluster.
- During our review call, we will discuss the following:
  - How would you get this system ready for production?
  - How would you make sure you can automate the development of this app?  Automated tests, deployment, etc.
