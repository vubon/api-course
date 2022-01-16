## API Development Course

### Django CLI Command Lines
1. Create app command
```text
python manage.py startapp <app Name>
```
2. Run Server
```text
python manage.py runserver
```
If you want to run the server in global mode. You can use below command
```text
python manage.py runserver 0.0.0.0:5000
```
3. Model Migrations <br>
i) For creating migration schema
```text
python manage.py makemigrations
```
ii) For migration migrations files
```text
python manage.py migrate 
```