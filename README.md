Buat folder namaproject,misal di d:
Tombol Start windows, ketik CMD, start via Administrator
cd d:/

pip install django
pip install django-admin
django-admin startproject websiteku
python manage.py createsuperuser
(Buat models.py dan admin.py)
python manage.py makemigrations websiteku
python manage.py migrate
python manage.py runserver

