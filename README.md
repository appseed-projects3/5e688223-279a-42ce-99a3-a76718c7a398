# [Gradient Able](https://appseed.us/generator/gradient-able/) Flask/Jinja

Open-source **Flask/Jinja Template** generated by `AppSeed` op top of **[Gradient Able](https://appseed.us/generator/gradient-able/)** a modern Bootstrap design. The project is a super simple Flask project WITHOUT database, ORM, or any other hard dependency. The project can be used as a codebase for future project or to migrate the Jinja files and assets to a legacy Python-based project that uses Jinja as template engine (Flask, Bottle, Django).
  
<br />

> Built with [Gradient Able Generator](https://appseed.us/generator/gradient-able/)

- 👉 [Gradient Able Flask](https://appseed.us/product/gradient-able/flask/) - Product page
- 👉 [Complete documentation](https://docs.appseed.us/boilerplate-code/boilerplate-jinja) - `Learn how to use and update the product`
- ✅ [PRO Version Available](https://appseed.us/product/gradient-able-pro/flask/) - `enhanced UI` and more `features` 

<br />

> Features

- `Up-to-date dependencies`
- Render Engine: Flask / [Jinja2](https://jinja.palletsprojects.com/)

<br />

![Gradient Able - Starter generated by AppSeed.](https://user-images.githubusercontent.com/51070104/171583187-c4ca1bef-b535-458e-9250-8d62ba1f5b30.png)

<br />



## ✨ How to use it

> Download the code 

```bash
$ # Get the code
$ git clone https://github.com/appseed-projects/5e688223-279a-42ce-99a3-a76718c7a398.git
$ cd 5e688223-279a-42ce-99a3-a76718c7a398
```

<br />

### 👉 Set Up for `Unix`, `MacOS` 

> Install modules via `VENV`  

```bash
$ virtualenv env
$ source env/bin/activate
$ pip3 install -r requirements.txt
```

<br />

> Set Up Flask Environment

```bash
$ export FLASK_APP=run.py
$ export FLASK_ENV=development
```

<br />

> Start the app

```bash
$ flask run
```

At this point, the app runs at `http://127.0.0.1:5000/`. 

<br />

### 👉 Set Up for `Windows` 

> Install modules via `VENV` (windows) 

```
$ virtualenv env
$ .\env\Scripts\activate
$ pip3 install -r requirements.txt
```

<br />

> Set Up Flask Environment

```bash
$ # CMD 
$ set FLASK_APP=run.py
$ set FLASK_ENV=development
$
$ # Powershell
$ $env:FLASK_APP = ".\run.py"
$ $env:FLASK_ENV = "development"
```

<br />

> Start the app

```bash
$ flask run
```

At this point, the app runs at `http://127.0.0.1:5000/`. 

<br />

## ✨ Code-base structure

The project has a simple, intuitive structure presented bellow:

```bash
< PROJECT ROOT >
   |
   |-- apps/__init__.py
   |-- apps/
   |    |-- static/
   |    |    |-- <css, JS, images>         # CSS files, Javascripts files
   |    |
   |    |-- templates/
   |         |
   |         |-- includes/                 # Page chunks, components
   |         |    |
   |         |    |-- navigation.html      # Top bar
   |         |    |-- sidebar.html         # Left sidebar
   |         |    |-- scripts.html         # JS scripts common to all pages
   |         |    |-- footer.html          # The common footer
   |         |
   |         |-- layouts/                  # App Layouts (the master pages)
   |         |    |
   |         |    |-- base.html            # Used by common pages like index, UI
   |         |    |-- base-fullscreen.html # Used by auth pages (login, register)
   |         |
   |      index.html                       # The default page
   |      page-404.html                    # Error 404 page (page not found)
   |      page-500.html                    # Error 500 page (server error)
   |         *.html                        # All other pages provided by the UI Kit
   |
   |-- requirements.txt
   |
   |-- run.py
   |
   |-- ************************************************************************
```

<br />

## ✨ Deploy APP with HEROKU

> The set up

- [Create a FREE account](https://signup.heroku.com/) on Heroku platform
- [Install the Heroku CLI](https://devcenter.heroku.com/articles/getting-started-with-python#set-up) that match your OS: Mac, Unix or Windows
- Open a terminal window and authenticate via `heroku login` command
- Clone the sources and push the project for LIVE deployment

<br />

> **Step 1** - Download the code from the GH repository (using `GIT`) 

```bash
$ # Get the code
$ git clone https://github.com/appseed-projects/<YOUR_BUILD_ID>.git
$ cd <YOUR_BUILD_ID>
```

<br />

> **Step 2** - Connect to `HEROKU` using the console

```bash
$ # This will open a browser window - click the login button (in browser)
$ heroku login
```
<br />

> **Step 3** - Create the `HEROKU` project

```bash
$ heroku create
```

<br />

> **Step 4** - Push Sources to `HEROKU`

```bash
$ git push heroku HEAD:master
```

<br />

> **Step 5** - Srt up the APP Environemnt in `HEROKU` (`.env` file is ignored by the platform)

- `DEBUG`=True
- `FLASK_APP`=run.py
- `FLASK_ENV`=development
- `ASSETS_ROOT`=/static/assets

![AppSeed - HEROKU Set UP](https://user-images.githubusercontent.com/51070104/171815176-c1ca7681-38cc-4edf-9ecc-45f93621573d.jpg)

<br />

> **Step 6** - Visit the app in the browser

```bash
$ $ heroku open
```

At this point, the APP should be up & running. 

<br />

> **Step 7** (Optional) - Visualize `HEROKU` logs

```bash
$ heroku logs --tail
```

<br />


## PRO Version

> For more components, pages and priority on support, feel free to take a look at this amazing starter:

Designed for those who like bold elements and beautiful websites, **Gradient Able** is the most stylish Bootstrap 4 Admin Template compare to all other Bootstrap admin templates. It comes with high feature-rich pages and components with fully developer-centric code. 

- 👉 [Flask Gradient PRO](https://appseed.us/product/gradient-able-pro/flask/) - product page
  - ✅ `Enhanced UI` - more pages and components
  - ✅ `Priority` on support

<br >

![Gradient Able PRO - Starter generated by AppSeed.](https://user-images.githubusercontent.com/51070104/171583582-d9652e7e-f420-4cf0-8eb1-dda3c79f8c18.png)

<br />

---
[Gradient Able](https://appseed.us/generator/gradient-able/) Flask/Jinja - Open-source starter generated by **[AppSeed Generator](https://appseed.us/generator/)**.
