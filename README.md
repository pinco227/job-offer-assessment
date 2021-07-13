# JobOffer
## DRF Level One Assessment Project
### [Udemy course](https://www.udemy.com/course/the-complete-guide-to-django-rest-framework-and-vue-js/)

The test consists in creating a Web API Project for a JobBoard website. Similar
to indeed.com, companies will be able to create and publish new job offers
that people will then be able to see.
Clients will be able to communicate with our Web API from 2 URL Endpoints:
1. ```api/jobs/``` - accepts `GET` and `POST` methods, allowing to create new
instances and retrieve a list with all the available job offer instances
2. ```api/jobs/<int:pk>/``` - accepts `GET`, `PUT` and `DELETE`, allowing a user to
retrieve, update or delete an object instance.

You can choose if you want to write the project views using the @api_view
decorator or the APIView class, and you can also choose to write the necessary
Serializer using the homonym class or the ModelSerializer class instead.

Only one model is needed for the project, you can call it JobOffer.
It must have the following fields:
- company_name
- company_email
- job_title
- job_description
- salary
- city
- state
- created_at
- available