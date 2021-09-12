![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

Welcome gwenjo,

This is the Code Institute student template for Gitpod. We have preinstalled all of the tools you need to get started. It's perfectly ok to use this template as the basis for your project submissions.

You can safely delete this README.md file, or change it for your own project. Please do read it at least once, though! It contains some important information about Gitpod and the extensions we use. Some of this information has been updated since the video content was created. The last update to this file was: **September 1, 2021**

## Gitpod Reminders

To run a frontend (HTML, CSS, Javascript only) application in Gitpod, in the terminal, type:

python3 -m http.server

python3 manage.py runserver

python3 manage.py startapp 

pip3 freeze > requirements.txt


cp -r ..//.pip-modules/lib/python3.8/site-packages/allauth/templates/* ./templates/allauth/ 

python3 manage.py loaddata ctegories
python3 manage.py loaddata products

python3 manage.py makemigrations --dry-run
python3 manage.py makemigrations

python3 manage.py migrate --plan
python3 manage.py migrate

export STRIPE_PUBLIC_KEY=pk_test_51JIHDOAae3eclnd3VlRgz2n3eYQqHen1CaCArxIWqOXRufHKNQ6Q9oMaaebUIMig2e7s3eHgaDjrsutCip5EPA0G00EsoG9jVy

export STRIPE_SECRET_KEY=sk_test_51JIHDOAae3eclnd3ojC0IlDBgb3equmNplZxmqup9Sds8rGjlmswL67TACMMnM9UcamHjTYcPyQVh6oFZWZ8fSpp00mB0Fmebi

export STRIPE_WH_SECRET=whsec_uDyWj5ad9RCafi8OOIDpigjY2LQYBOXt