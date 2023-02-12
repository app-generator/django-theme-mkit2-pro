# **[Django Theme MKit 2 PRO](https://appseed.us/product/material-kit2-pro/django/)**

**Django** starter styled with **[Material Kit2 PRO](https://appseed.us/product/material-kit2-pro/django/)**, a premium `Boostrap 5` design from [Creative-Tim](https://bit.ly/3fKQZaL)
The product is designed to deliver the best possible user experience with highly customizable feature-rich pages. 

> 👉 **NOTE**: This product `requires a License` in order to access the theme:

**Private REPO**: `git+https://github.com/app-generator/priv-django-theme-mkit2-pro`

<br />

## Features: 

- **UI Kit**: Material Kit2 BS5 PRO `v3.0.3` by Creative-Tim
- [Django MKit 2 PRO](https://appseed.us/product/material-kit2-pro/django/) - `sample project`
- **Sections Covered**: 
  - `All pages` managed by `Django.contrib.AUTH`
  - `Registration` page
  - `Misc pages`: colors, icons, typography, blank-page ..etc

<br />

![Material Kit 2 Pro](https://user-images.githubusercontent.com/51070104/211263795-a166b69b-ba59-43a1-9be5-69b1cc36d786.png)

<br />

## Why `Django Theme MKit 2 PRO`

- Modern [Bootstrap 5](https://www.admin-dashboards.com/bootstrap-5-templates/) Design
- `Responsive Interface`
- `Minimal Template` overriding
- `Easy integration`

Designed for those who like bold elements and beautiful websites. Made of hundred of elements, designed blocks, and fully coded pages, Material Kit 2 PRO is ready to help you create stunning websites and web apps.

<br />

## How to use it

<br />

> **Install the package** via `PIP` 

```bash
$ pip install git+https://github.com/app-generator/priv-django-theme-mkit2-pro.git
```

<br />

> Add `theme_mkit2_pro` application to the `INSTALLED_APPS` setting of your Django project `settings.py` file:

```python
    INSTALLED_APPS = (
        ...
        "django.contrib.admin",
        "django.contrib.auth",
        "django.contrib.contenttypes",
        "django.contrib.sessions",
        "django.contrib.messages",
        "django.contrib.staticfiles",
        ...
        'theme_mkit2_pro',            # <-- NEW
    )
```

<br />

> Add `LOGIN_REDIRECT_URL` and `EMAIL_BACKEND` of your Django project `settings.py` file:

```python
    LOGIN_REDIRECT_URL = '/'
    # EMAIL_BACKEND = 'django.core.mail.backends.smtp.EmailBackend'
    EMAIL_BACKEND = 'django.core.mail.backends.console.EmailBackend'
```

<br />

> Add `theme_mkit2_pro` urls in your Django Project `urls.py` file

```python
    from django.urls import path, include

    urlpatterns = [
        ...
        path('', include('theme_mkit2_pro.urls')),
    ]
```

<br />

> **Collect static** if you are in `production environment`:

```bash
$ python manage.py collectstatic
```

<br />

> **Start the app**

```bash
$ # Set up the database
$ python manage.py makemigrations
$ python manage.py migrate
$
$ # Create the superuser
$ python manage.py createsuperuser
$
$ # Start the application (development mode)
$ python manage.py runserver # default port 8000
```

Access the `admin` section in the browser: `http://127.0.0.1:8000/`

<br />

## Screenshots

![Django Theme MKit 2 PRO - UI Component.](https://user-images.githubusercontent.com/51070104/212049122-e98794ef-7487-492b-919b-32118145fd34.png)

<br />

> [Django Theme MKit 2 PRO](https://appseed.us/product/material-kit2-pro/django/) - `Rental page`

![Django Theme MKit 2 PRO - Rental Page](https://user-images.githubusercontent.com/51070104/212049863-b33f921b-1e7f-4f96-a675-14f649aa46eb.png) 

<br />

---
**[Django Theme MKit 2 PRO](https://appseed.us/product/material-kit2-pro/django/)** - Modern Theme provided by **[AppSeed](https://appseed.us/)**
