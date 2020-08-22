# CRM-App-Django
I had it up on rajitrajpal.herokuapp.com but I took it down due to an SQL injection attack that costed me some momey :/
To use it on your system, run:
```bash
pip install -r requirements.txt
```
Then create an admin user logic info:
```bash
python manage.py createsuperuser
```
Run Migrations:
```bash
python manage.py makemigrations
```
```bash
python manage.py migrate
```
This next script allows you to run it on localhost:8000:
```bash
python manage.py runserver
```
###Dashboard
![Screenshot](Capture.png)

###Admin
![Screenshot](Capture1.png)

## License
[MIT](https://choosealicense.com/licenses/mit/)
