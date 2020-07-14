# Product_Hunt_Django

Product Hunt

Product Hunt is a review posting site developed in Django. Where user can Register, Login Then add review. User can like review, Update their own profile, Edit their posted review also can delete them. There is a comment system implement for each review.
Requirements

open requirements.txt file to see requirements

Installing

open terminal and type

git remote add origin https://github.com/Nayan-Code/Product_Hunt_Django.git

or simply download using the url below
git remote add origin https://github.com/Nayan-Code/Product_Hunt_Django.git
To migrate the database open terminal in project directory and type
python manage.py makemigrations
python manage.py migrate
Static files collection

open terminal and type

python manage.py collectstatic
Creating Superuser

To create superuser open terminal and type

python manage.py createsuperuser

Then go to http://127.0.0.1:8000 in your browser
