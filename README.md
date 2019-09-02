# mysite

> A django blog website based project project

## Build Setup

``` bash
# install dependencies
python install -r requiement.txt

# serve with hot reload at localhost:8080
python manage.py runserve

# To add an app to the project
python manage.py startapp <app_name>

# Added the "personal" app using
python manage.py startapp personal

# Added the "account" app using
python manage.py startapp account

# After creating an app make sure to add it to project go to "mysite/settings.py" files under INSTALLED_APP section add as follows :-
'<app_name>.apps.<App_name>Congig',

    eg., app name is personal
    INSTALLED_APP = [
        'personal.apps.PersonalConfig',
        ........
        ........
        "DEFAULT_PROJECT_APPS 
        avoid editing unless you are not sure"
        .........
        .........
    ]

# run unit tests

```

For a detailed explanation on how things work, check out the [course](https://codingwithmitch.com/courses/building-a-website-django-python/) and [docs for django](https://docs.djangoproject.com/en/2.2/).
