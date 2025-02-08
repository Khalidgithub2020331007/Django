```
rm -rf home/migrations/
touch home/migrations/init.py
python3 manage.py makemigrations home
python3 manage.py migrate
```
