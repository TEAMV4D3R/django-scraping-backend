# Django Scraping Backend

This is where we have created the data model for storing the scraped recommended jobs information for the user. The data model includes the scraped job position titles, locations, company, the job application URL and the time and date created. This backend has been containerized for deployment. This backend was created from a template for which the initialization information is below. 

## api-quick-start

Template Project for starting up CRUD API with Django Rest Framework

## Customization Steps

- DO NOT migrate yet
- add additional dependencies as needed
  - Re-export requirements.txt as needed
- change `things` folder to the app name of your choice
- Search through entire code base for `Thing`,`Things` and `things` to modify code to use your resource
  - `project/settings.py`
  - `project/urls.py`
  - App's files
    - `views.py`
    - `urls.py`
    - `admin.py`
    - `serializers.py`
    - `permissions.py`
- Update ThingModel with fields you need
  - Make sure to update other modules that would be affected by Model customizations. E.g. serializers, tests, etc.
- Rename `project/.env.sample` to `.env` and update as needed
- Run makemigrations and migrate commands
- Run `collectstatic` if needed.
- Optional: Update `api_tester.py`


## Sources

Django Model Inlines <https://www.jbssolutions.com/resources/blog/improve-djangos-admin-interface-using-inlines/>
