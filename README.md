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

python3 manage.py loaddata categories
python3 manage.py loaddata products

python3 manage.py makemigrations --dry-run
python3 manage.py makemigrations

python3 manage.py migrate --plan
python3 manage.py migrate

export STRIPE_PUBLIC_KEY=pk_test_51Ji2ydExh6k37O8drfR8DW0WFC5FpdCVh7fqE3KoQ5zbF4BIPWq3EPPo8YfqxWWY88TYAQlZJcz4NPTxk0zwRz7b003paA4F4C

export STRIPE_SECRET_KEY=sk_test_51Ji2ydExh6k37O8dIp2DZPmsghaVXGM17faW5b9eS7gxViaikEcSfXgbfHyMmFUenvcyXqcPYmpH4lzuiNH4ftcA00tgw0Many

export STRIPE_WH_SECRET=whsec_VS0KMd55gltaPwk8oGAuYoqluJB6QLIO