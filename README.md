Buat folder namaproject,misal di d:
Laragon -> Terminal
cd d:/
cd namaproject
ls
(pastikan ada file manage.py)

pip install django
pip install django-admin
django-admin startproject pandroid
python manage.py createsuperuser
(Buat models.py dan admin.py)
python manage.py makemigration pandroid
python manage.py migrate pandroid
python manage.py runserver

